# Changes since 2021-05-16

## Changes in Algorithm

- [#6173](https://github.com/AliceO2Group/AliceO2/pull/6173) 2021-05-17: GPU: Split host and GPU code during CUDA compilation, mostly for faster compilation by [@davidrohr](https://github.com/davidrohr)
## Changes in Analysis

- [#6182](https://github.com/AliceO2Group/AliceO2/pull/6182) 2021-05-17: Fix comment by [@jgrosseo](https://github.com/jgrosseo)
- [#6176](https://github.com/AliceO2Group/AliceO2/pull/6176) 2021-05-18: Analysis: remove deprecated HistHelpers by [@mario-krueger](https://github.com/mario-krueger)
- [#6191](https://github.com/AliceO2Group/AliceO2/pull/6191) 2021-05-20: Further updates of tutorials by [@pbuehler](https://github.com/pbuehler)
- [#6220](https://github.com/AliceO2Group/AliceO2/pull/6220) 2021-05-21: Event selection adapted to Run2 and Run3 MC by [@ekryshen](https://github.com/ekryshen)
- [#6232](https://github.com/AliceO2Group/AliceO2/pull/6232) 2021-05-22: Do not use printf by [@ktf](https://github.com/ktf)
- [#6225](https://github.com/AliceO2Group/AliceO2/pull/6225) 2021-05-25: DPL Analysis: Handle unassigned (-1) index in grouping by [@aalkin](https://github.com/aalkin)
- [#6237](https://github.com/AliceO2Group/AliceO2/pull/6237) 2021-05-25: Fixes in doxygen: by [@ihrivnac](https://github.com/ihrivnac)
- [#6254](https://github.com/AliceO2Group/AliceO2/pull/6254) 2021-05-27: Avoid tuple in analysis task by [@ktf](https://github.com/ktf)
- [#6255](https://github.com/AliceO2Group/AliceO2/pull/6255) 2021-05-28: PWGHF: Fix track selection in index skimming by [@vkucera](https://github.com/vkucera)
- [#6271](https://github.com/AliceO2Group/AliceO2/pull/6271) 2021-05-30: PWGHF: Switch MC on by default by [@vkucera](https://github.com/vkucera)
## Changes in Common

- [#6173](https://github.com/AliceO2Group/AliceO2/pull/6173) 2021-05-17: GPU: Split host and GPU code during CUDA compilation, mostly for faster compilation by [@davidrohr](https://github.com/davidrohr)
- [#6211](https://github.com/AliceO2Group/AliceO2/pull/6211) 2021-05-20: DPL: use Resource Manager to optimize shared memory usage by [@ktf](https://github.com/ktf)
- [#6181](https://github.com/AliceO2Group/AliceO2/pull/6181) 2021-05-20: Introducing simulation as a service by [@sawenzel](https://github.com/sawenzel)
## Changes in DataFormats

- [#6177](https://github.com/AliceO2Group/AliceO2/pull/6177) 2021-05-18: Add FT0 Channels to RecPointReader and RecContainer by [@shahor02](https://github.com/shahor02)
- [#6228](https://github.com/AliceO2Group/AliceO2/pull/6228) 2021-05-21: missing includes to compile with gcc11 by [@wiechula](https://github.com/wiechula)
- [#6187](https://github.com/AliceO2Group/AliceO2/pull/6187) 2021-05-22: moved Calib objects to DataFormats; Reimplement clusters as obj. with… by [@peressounko](https://github.com/peressounko)
- [#6236](https://github.com/AliceO2Group/AliceO2/pull/6236) 2021-05-24: BadChannelsMap renamed by [@peressounko](https://github.com/peressounko)
- [#6242](https://github.com/AliceO2Group/AliceO2/pull/6242) 2021-05-26: [TRD] remove tabs and trailing whitespaces by [@martenole](https://github.com/martenole)
- [#6247](https://github.com/AliceO2Group/AliceO2/pull/6247) 2021-05-28: Headers: remove unneeded traits by [@ktf](https://github.com/ktf)
## Changes in Detectors

- [#6180](https://github.com/AliceO2Group/AliceO2/pull/6180) 2021-05-17: Add default c-tors to PVertex debug dump objects by [@shahor02](https://github.com/shahor02)
- [#6172](https://github.com/AliceO2Group/AliceO2/pull/6172) 2021-05-17: Fix in VertexTrackMatcher ITS track time treatment by [@shahor02](https://github.com/shahor02)
- [#6177](https://github.com/AliceO2Group/AliceO2/pull/6177) 2021-05-18: Add FT0 Channels to RecPointReader and RecContainer by [@shahor02](https://github.com/shahor02)
- [#6199](https://github.com/AliceO2Group/AliceO2/pull/6199) 2021-05-18: Fix HMPID stream decoder workflow writing output at end of run not at endOfStream by [@davidrohr](https://github.com/davidrohr)
- [#6189](https://github.com/AliceO2Group/AliceO2/pull/6189) 2021-05-18: Fix in composition of ITS/MFT dictionary name by [@shahor02](https://github.com/shahor02)
- [#6195](https://github.com/AliceO2Group/AliceO2/pull/6195) 2021-05-18: Update CompressorTask.cxx by [@preghenella](https://github.com/preghenella)
- [#6210](https://github.com/AliceO2Group/AliceO2/pull/6210) 2021-05-19: Fix for a typo in FT0 RecPointReaderSpec (from N.Burmasov) by [@shahor02](https://github.com/shahor02)
- [#6188](https://github.com/AliceO2Group/AliceO2/pull/6188) 2021-05-19: Log statistics on track to vertex assignment by [@shahor02](https://github.com/shahor02)
- [#6192](https://github.com/AliceO2Group/AliceO2/pull/6192) 2021-05-19: MCH: check HB packet validity in UL decoder by [@aferrero2707](https://github.com/aferrero2707)
- [#6193](https://github.com/AliceO2Group/AliceO2/pull/6193) 2021-05-19: MCH: improved time frame grouping in CRU page reader by [@aferrero2707](https://github.com/aferrero2707)
- [#6205](https://github.com/AliceO2Group/AliceO2/pull/6205) 2021-05-19: [MFT] Marking reconstructed tracks on the MC AOD table by [@rpezzi](https://github.com/rpezzi)
- [#6200](https://github.com/AliceO2Group/AliceO2/pull/6200) 2021-05-20: FT0: correct treatment of missing TF by [@shahor02](https://github.com/shahor02)
- [#6198](https://github.com/AliceO2Group/AliceO2/pull/6198) 2021-05-20: Fix in ITS digits->raw conversion by [@shahor02](https://github.com/shahor02)
- [#6194](https://github.com/AliceO2Group/AliceO2/pull/6194) 2021-05-20: Update CompressorTask.cxx by [@preghenella](https://github.com/preghenella)
- [#6207](https://github.com/AliceO2Group/AliceO2/pull/6207) 2021-05-20: [MCH] prepare setup for run3 by [@pillot](https://github.com/pillot)
- [#6206](https://github.com/AliceO2Group/AliceO2/pull/6206) 2021-05-20: minor fixes in TPC CalArray and TPC/qc PID by [@tklemenz](https://github.com/tklemenz)
- [#6228](https://github.com/AliceO2Group/AliceO2/pull/6228) 2021-05-21: missing includes to compile with gcc11 by [@wiechula](https://github.com/wiechula)
- [#6229](https://github.com/AliceO2Group/AliceO2/pull/6229) 2021-05-22: GPU: Option renaming, and grouping of TRD and TPC options by [@davidrohr](https://github.com/davidrohr)
- [#6187](https://github.com/AliceO2Group/AliceO2/pull/6187) 2021-05-22: moved Calib objects to DataFormats; Reimplement clusters as obj. with… by [@peressounko](https://github.com/peressounko)
- [#6233](https://github.com/AliceO2Group/AliceO2/pull/6233) 2021-05-23: Suppress leftover PHOSCalib directory [fix for PR6187] by [@shahor02](https://github.com/shahor02)
- [#6234](https://github.com/AliceO2Group/AliceO2/pull/6234) 2021-05-23: fix in CCDB populator documentation by [@shahor02](https://github.com/shahor02)
- [#6236](https://github.com/AliceO2Group/AliceO2/pull/6236) 2021-05-24: BadChannelsMap renamed by [@peressounko](https://github.com/peressounko)
- [#6202](https://github.com/AliceO2Group/AliceO2/pull/6202) 2021-05-24: rANS: allow encoders/decoders with empty dictionaries by [@shahor02](https://github.com/shahor02)
- [#6237](https://github.com/AliceO2Group/AliceO2/pull/6237) 2021-05-25: Fixes in doxygen: by [@ihrivnac](https://github.com/ihrivnac)
- [#6242](https://github.com/AliceO2Group/AliceO2/pull/6242) 2021-05-26: [TRD] remove tabs and trailing whitespaces by [@martenole](https://github.com/martenole)
- [#6262](https://github.com/AliceO2Group/AliceO2/pull/6262) 2021-05-27: More fixes in doxygen: by [@ihrivnac](https://github.com/ihrivnac)
- [#6230](https://github.com/AliceO2Group/AliceO2/pull/6230) 2021-05-28: MFT Noise calibration by [@mcoquet642](https://github.com/mcoquet642)
## Changes in EventVisualisation

- [#6175](https://github.com/AliceO2Group/AliceO2/pull/6175) 2021-05-20: implementation of active watching folder for files with tracks by [@jmyrcha](https://github.com/jmyrcha)
- [#6186](https://github.com/AliceO2Group/AliceO2/pull/6186) 2021-05-20: saving tracks from workflow to jsons by [@jmyrcha](https://github.com/jmyrcha)
## Changes in Examples

- [#6181](https://github.com/AliceO2Group/AliceO2/pull/6181) 2021-05-20: Introducing simulation as a service by [@sawenzel](https://github.com/sawenzel)
- [#6221](https://github.com/AliceO2Group/AliceO2/pull/6221) 2021-05-21: o2-sim: Improve communication between primary server and transport wo… by [@sawenzel](https://github.com/sawenzel)
## Changes in Framework

- [#6182](https://github.com/AliceO2Group/AliceO2/pull/6182) 2021-05-17: Fix comment by [@jgrosseo](https://github.com/jgrosseo)
- [#6184](https://github.com/AliceO2Group/AliceO2/pull/6184) 2021-05-18: Documentation of the Analysis Framework is moved by [@pbuehler](https://github.com/pbuehler)
- [#6215](https://github.com/AliceO2Group/AliceO2/pull/6215) 2021-05-20: DPL: hotfix for resource manager by [@ktf](https://github.com/ktf)
- [#6211](https://github.com/AliceO2Group/AliceO2/pull/6211) 2021-05-20: DPL: use Resource Manager to optimize shared memory usage by [@ktf](https://github.com/ktf)
- [#6208](https://github.com/AliceO2Group/AliceO2/pull/6208) 2021-05-20: Dropping old / obsolete / unmaintained code by [@ktf](https://github.com/ktf)
- [#6178](https://github.com/AliceO2Group/AliceO2/pull/6178) 2021-05-21: AliECS dump: A bunch of various improvements by [@knopers8](https://github.com/knopers8)
- [#6212](https://github.com/AliceO2Group/AliceO2/pull/6212) 2021-05-21: DPL: add test for ability to create transport by [@ktf](https://github.com/ktf)
- [#6218](https://github.com/AliceO2Group/AliceO2/pull/6218) 2021-05-21: DPL: properly handle SIGTERM by [@ktf](https://github.com/ktf)
- [#6228](https://github.com/AliceO2Group/AliceO2/pull/6228) 2021-05-21: missing includes to compile with gcc11 by [@wiechula](https://github.com/wiechula)
- [#6225](https://github.com/AliceO2Group/AliceO2/pull/6225) 2021-05-25: DPL Analysis: Handle unassigned (-1) index in grouping by [@aalkin](https://github.com/aalkin)
- [#6238](https://github.com/AliceO2Group/AliceO2/pull/6238) 2021-05-25: DPL Analysis: Update histogram registry spec to make it more distinguishable by [@saganatt](https://github.com/saganatt)
- [#6197](https://github.com/AliceO2Group/AliceO2/pull/6197) 2021-05-25: Have to use FATAL message to catch failure condition in workflow unit… by [@matthiasrichter](https://github.com/matthiasrichter)
- [#6241](https://github.com/AliceO2Group/AliceO2/pull/6241) 2021-05-26: Fix parsing for InputSpec with DataOrigin only by [@shahor02](https://github.com/shahor02)
- [#6254](https://github.com/AliceO2Group/AliceO2/pull/6254) 2021-05-27: Avoid tuple in analysis task by [@ktf](https://github.com/ktf)
- [#6256](https://github.com/AliceO2Group/AliceO2/pull/6256) 2021-05-27: DPL: improve workflow validation by [@ktf](https://github.com/ktf)
- [#6217](https://github.com/AliceO2Group/AliceO2/pull/6217) 2021-05-28: DPL Analysis: send the size of the tables as metric by [@ktf](https://github.com/ktf)
- [#6240](https://github.com/AliceO2Group/AliceO2/pull/6240) 2021-05-28: DPL: improve shared memory handling in AOD by [@ktf](https://github.com/ktf)
- [#6268](https://github.com/AliceO2Group/AliceO2/pull/6268) 2021-05-29: DPL: rationalise parent-child communication by [@ktf](https://github.com/ktf)
## Changes in Generators

- [#6181](https://github.com/AliceO2Group/AliceO2/pull/6181) 2021-05-20: Introducing simulation as a service by [@sawenzel](https://github.com/sawenzel)
## Changes in Steer

- [#6181](https://github.com/AliceO2Group/AliceO2/pull/6181) 2021-05-20: Introducing simulation as a service by [@sawenzel](https://github.com/sawenzel)
- [#6239](https://github.com/AliceO2Group/AliceO2/pull/6239) 2021-05-25: Fix: QED interaction sampler was using default BC scheme by [@shahor02](https://github.com/shahor02)
## Changes in Utilities

- [#6208](https://github.com/AliceO2Group/AliceO2/pull/6208) 2021-05-20: Dropping old / obsolete / unmaintained code by [@ktf](https://github.com/ktf)
- [#6202](https://github.com/AliceO2Group/AliceO2/pull/6202) 2021-05-24: rANS: allow encoders/decoders with empty dictionaries by [@shahor02](https://github.com/shahor02)
- [#6245](https://github.com/AliceO2Group/AliceO2/pull/6245) 2021-05-26: Grep logfile always as ascii file not as binary in jobutils.sh by [@davidrohr](https://github.com/davidrohr)
