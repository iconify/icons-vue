<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="j_dulcbnt"/><path fill="url(#iAlKUYw)" class="ng-28zxwb"/><path fill="url(#itbtQzd)" class="ng-28zxwb"/><path fill="url(#iOhOn5b)" class="ng-28zxwb"/><path fill="url(#i8ngfnv)" class="ng-28zxwb"/><path fill="url(#ilxDSxc)" class="ng-28zxwb"/><path class="em148031i"/><path fill="url(#iAomAlC)" class="tnef9wrdf"/><path fill="url(#ig9e68k)" class="tnef9wrdf"/><path fill="url(#iB0vApd)" class="tnef9wrdf"/><g filter="url(#iFowyve)"><path class="z_czc81-p"/></g><path fill="url(#i27EXBe)" class="g7gmqhncd"/><path fill="url(#im8Vkvd)" class="g7gmqhncd"/><path fill="url(#i39ExJd)" class="g7gmqhncd"/><path fill="url(#iWKZSod)" class="by194g1ei"/><path fill="url(#idsRMlc)" class="by194g1ei"/><g filter="url(#idysBLQ)"><path fill="url(#ieVAJKD)" class="gemgotgww"/></g><path fill="url(#iOeoa4b)" class="zswbabceh"/><path fill="url(#im9eHqM)" class="zswbabceh"/><path fill="url(#iTudamq)" class="zswbabceh"/><path fill="url(#iEbPnCK)" class="wibdzhbon"/><path fill="url(#itSm4AK)" class="wibdzhbon"/><path fill="url(#iEpqGnc)" class="wibdzhbon"/><path fill="url(#iHu3LFd)" class="wibdzhbon"/><path fill="url(#iP6c0ue)" class="wibdzhbon"/><path class="yyxxh9qfh"/><path fill="url(#iyKMIle)" class="s0-op-jbm"/><path fill="url(#iC6TSsc)" class="s0-op-jbm"/><path fill="url(#i7oZ1zb)" class="s0-op-jbm"/><path fill="url(#ira2lKd)" class="s0-op-jbm"/><path fill="url(#iknlR1o)" class="s0-op-jbm"/><path fill="url(#itwuFuQ)" class="j-ut2xl5o"/><path fill="url(#iWj2Jee)" class="j-ut2xl5o"/><g filter="url(#izDQT8w)"><path fill="url(#iimzjsu)" class="mop_zlbnl"/><path fill="url(#iwOdF4c)" class="mop_zlbnl"/><path fill="url(#iMAGDRc)" class="mop_zlbnl"/><path fill="url(#i2jMWwb)" class="mop_zlbnl"/><path fill="url(#isZI5dk)" class="mop_zlbnl"/></g><g filter="url(#iJvFfPc)"><path fill="url(#i1VflDU)" class="xhfhhvoed"/><path fill="url(#iEAfnnc)" class="xhfhhvoed"/><path fill="url(#isUiL6c)" class="xhfhhvoed"/><path fill="url(#iVjF54c)" class="xhfhhvoed"/></g><path fill="url(#ivSwZae)" class="rhxl5gb9p"/><path fill="url(#iax88fe)" class="rhxl5gb9p"/><rect fill="url(#iz2Begd)" class="erhkeibcy"/><rect fill="url(#iWBccNc)" class="erhkeibcy"/><rect fill="url(#ih9GmGc)" class="erhkeibcy"/><rect fill="url(#iJ8MAGd)" class="erhkeibcy"/><g filter="url(#isKG75X)"><circle class="k7e504bil"/></g><circle fill="url(#iU1hsCv)" class="vd-u4acdq"/><circle fill="url(#i5Fhu0c)" class="vd-u4acdq"/><g filter="url(#iG5WOSW)"><path fill="url(#iIrRcKb)" clip-rule="evenodd" class="g1ovp4bwp"/></g><rect fill="url(#ihSbEiX)" transform="rotate(-30 25.512 15.977)" class="tjiypub2l"/><g filter="url(#iqDUSDd)"><path fill="url(#i8X5aed)" class="ws-9x4b9n"/><path fill="url(#i6It0Mc)" class="ws-9x4b9n"/><path fill="url(#iRDJC0b)" class="ws-9x4b9n"/><path fill="url(#isG2Jnb)" class="ws-9x4b9n"/><path fill="url(#iptqFYb)" class="ws-9x4b9n"/></g><path fill="url(#ivKkQAc)" class="ws-9x4b9n"/><g filter="url(#iZYVphe)"><path stroke="url(#iep2WYd)" class="fkavrburz"/></g><g filter="url(#ioiF0Cc)"><path stroke="url(#i0UPD0b)" class="tnviirb6b"/></g><g filter="url(#ik0Z38d)"><path stroke="url(#iaOTrJt)" class="bc7i0ongh"/></g><g filter="url(#iijjmtd)"><circle fill="url(#iUkmTke)" class="mh39h7hpm"/></g><g filter="url(#i0Odijm)"><circle fill="url(#iCsv2Eb)" class="yzf80p4jc"/></g><g filter="url(#ipSU0Zd)"><circle class="yxzzhscvi"/><circle fill="url(#iYJXkkb)" class="n0h_63bcp"/><circle fill="url(#ijtguZw)" class="n0h_63bcp"/></g><g filter="url(#i8zzRRb)"><circle fill="url(#iZoqDFv)" class="hqp1wu_he"/></g><g filter="url(#i06l8Yd)"><path fill="url(#ivR4fJe)" class="hknh16mic"/><path fill="url(#inAvxxb)" class="hknh16mic"/></g><path fill="url(#iFWksLF)" class="hknh16mic"/><path fill="url(#i3mBfMe)" class="hknh16mic"/><path fill="url(#iqnuXpd)" class="hknh16mic"/><path fill="url(#iRJ6jbe)" class="hknh16mic"/><path fill="url(#i9peNse)" class="hknh16mic"/><g filter="url(#i17Wffb)"><path class="bgcqg98jc"/></g><g filter="url(#iGkbqsd)"><path class="i0-8psn3d"/><path fill="url(#iEu1kid)" class="sxgpvtb4k"/><path fill="url(#iLm197d)" class="sxgpvtb4k"/><path fill="url(#iT5Gk9b)" class="sxgpvtb4k"/></g><g filter="url(#i787x9c)"><path fill="url(#iTbGMGd)" class="kdvr4u58b"/></g><g filter="url(#iFmji1b)"><path stroke="url(#iWrix3d)" class="kqcubybll"/></g><path class="fldt-ebmj"/><path class="n3m4ul9nu"/><path fill="url(#iTIY5Qc)" class="e1av8fbyb"/><path class="rrgrst12i"/><g filter="url(#ifgUYqb)"><path class="tkuxygb0m"/><path fill="url(#icmYJFc)" class="ghq__ebhv"/></g><g filter="url(#i9Asvhc)"><path fill="url(#iE5JQae)" class="f-gl8-mln"/></g><path class="x8vyagemg"/><path fill="url(#iTecODJ)" class="y_qlpp2fu"/><path class="mibx7d57r"/><g filter="url(#iLjMXUb)"><path fill="url(#iN3jgZV)" class="v9c6zoseo"/></g><g filter="url(#ipwekXd)"><ellipse transform="rotate(-27.914 11.99 11.986)" class="y-v21bc8n"/><ellipse fill="url(#iFbcshM)" transform="rotate(-27.914 11.99 11.986)" class="ljhgv1b3v"/></g><path fill="url(#i6dlANQ)" class="kdzxr8bcy"/><path fill="url(#iRhuwwe)" class="kdzxr8bcy"/><path fill="url(#irLEf8c)" class="ijrk-tbbt"/><g filter="url(#iUMVclc)"><path fill="url(#i8gh6Fe)" class="ivj3pk5jv"/></g><path fill="url(#iBfj5Pd)" class="ivj3pk5jv"/><path fill="url(#ieAjMmb)" class="ivj3pk5jv"/><g filter="url(#iSSqK7b)"><path fill="url(#iodu1md)" class="jpbxw370c"/></g><path fill="url(#iTUCPGc)" class="dnfp-euku"/><path fill="url(#iAJlZRd)" class="dnfp-euku"/><path fill="url(#iLKj4pc)" class="dnfp-euku"/><path fill="url(#iAYhuWd)" class="dnfp-euku"/><defs><radialGradient id="iAlKUYw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.813)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="itbtQzd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.441 11.476)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="i8ngfnv" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.836 22.157)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="ilxDSxc" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.417 66.253)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="ig9e68k" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .522 17.985)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="iB0vApd" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.586 20.885)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="i27EXBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="im8Vkvd" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.545 12.698)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="i39ExJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="iWKZSod" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.47)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="idsRMlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.921)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="ieVAJKD" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.859 22.655)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="iOeoa4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.782)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="iEbPnCK" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.97)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="iEpqGnc" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.196 14.246)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="iHu3LFd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.135 8.129)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iP6c0ue" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.048 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iyKMIle" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.47)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="i7oZ1zb" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.372 20.583)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ira2lKd" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.576)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iknlR1o" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.7 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="itwuFuQ" cx="0" cy="0" r="1" gradientTransform="matrix(3.6691 1.75022 -1.69627 3.55598 13.456 19.388)" gradientUnits="userSpaceOnUse"><stop class="l50s_ac3p"/><stop offset=".433" class="xp457mbaj"/><stop offset=".66" class="xp457mbaj"/><stop offset="1" class="js34-kdjw"/></radialGradient><radialGradient id="iWj2Jee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87624 -2.99056 0 14.875 19.547)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="hb-nqccyv"/><stop offset="1" class="gtmei0bfc"/></radialGradient><radialGradient id="iMAGDRc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.398 8.283)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="isZI5dk" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.317 21.252)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="isUiL6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.25)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="iVjF54c" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.39 12.983)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="ivSwZae" cx="0" cy="0" r="1" gradientTransform="rotate(154.424 11.774 14.943)scale(2.5843 2.53551)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="fwxdqq60h"/><stop offset="1" class="sn5q5zbjv"/></radialGradient><radialGradient id="iax88fe" cx="0" cy="0" r="1" gradientTransform="matrix(.88698 -.597 .4575 .67972 28.125 22.694)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wa3u08nda"/><stop offset="1" class="aszpk2bre"/><stop offset="1" class="f-jevn7df"/></radialGradient><radialGradient id="ih9GmGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.227)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="iJ8MAGd" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.266)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iU1hsCv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.25)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="i5Fhu0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.73)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="ihSbEiX" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.119)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="i6It0Mc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8752 -1.60814 0 26.025 24.797)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iRDJC0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93815 -1.72383 0 26.025 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="isG2Jnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78463 -1.44175 0 26.025 27.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iptqFYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87265 -2.05091 0 26.025 29.05)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iUkmTke" cx="0" cy="0" r="1" gradientTransform="rotate(83.775 -2.496 11.44)scale(1.9296)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="n6k7cjgpd"/><stop offset="1" class="aknm_exmg"/></radialGradient><radialGradient id="iCsv2Eb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56385 0 0 -1.00365 8.997 12.72)" gradientUnits="userSpaceOnUse"><stop class="j3zeyq-sj"/><stop offset="1" class="j0dv9ngke"/></radialGradient><radialGradient id="iYJXkkb" cx="0" cy="0" r="1" gradientTransform="rotate(150.173 9.425 8.78)scale(1.41063 1.31947)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="y__sil0st"/><stop offset="1" class="lcv6zvemz"/></radialGradient><radialGradient id="ijtguZw" cx="0" cy="0" r="1" gradientTransform="matrix(1.2564 -.84872 .734 1.08658 20.68 14.599)" gradientUnits="userSpaceOnUse"><stop class="tvwclb40x"/><stop offset="1" class="kbjnrqkvo"/></radialGradient><radialGradient id="iZoqDFv" cx="0" cy="0" r="1" gradientTransform="matrix(.93042 0 0 .9847 20.5 12.761)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="ee70-8_hv"/><stop offset="1" class="o-88nes6c"/></radialGradient><radialGradient id="ivR4fJe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09082 4.20865 -6.92602 -8.37778 19.115 14.8)" gradientUnits="userSpaceOnUse"><stop class="c1vbzi-sh"/><stop offset="1" class="p12q4lqjb"/></radialGradient><radialGradient id="inAvxxb" cx="0" cy="0" r="1" gradientTransform="rotate(25.039 -32.399 39.347)scale(3.53387 3.49856)" gradientUnits="userSpaceOnUse"><stop class="cw4t4r-fb"/><stop offset="1" class="dmg57hbhe"/></radialGradient><radialGradient id="iFWksLF" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71703 -15.3444 0 14.844 12.32)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="zknvtjbtz"/><stop offset="1" class="zglqorbou"/></radialGradient><radialGradient id="i3mBfMe" cx="0" cy="0" r="1" gradientTransform="rotate(157.563 6.99 6.367)scale(9.28257 4.85811)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="w5xgflzkx"/><stop offset="1" class="f9qu94gfh"/></radialGradient><radialGradient id="iqnuXpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.79462 -1.91111 0 20.804 11.15)" gradientUnits="userSpaceOnUse"><stop class="icczjvbzw"/><stop offset="1" class="onow8rbko"/></radialGradient><radialGradient id="iRJ6jbe" cx="0" cy="0" r="1" gradientTransform="rotate(141.373 3.952 8.06)scale(2.47951 1.88304)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="vz-bod6vj"/><stop offset="1" class="crspr0bkb"/></radialGradient><radialGradient id="i9peNse" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42608 -2.01711 0 17.577 12.273)" gradientUnits="userSpaceOnUse"><stop class="fce7k9bpt"/><stop offset="1" class="pxopwiwar"/><stop offset="1" class="ug62x2bvv"/></radialGradient><radialGradient id="iEu1kid" cx="0" cy="0" r="1" gradientTransform="matrix(-.87264 0 0 -.32232 15.421 14.504)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="v6_19y23u"/><stop offset="1" class="c07mg7bed"/></radialGradient><radialGradient id="iLm197d" cx="0" cy="0" r="1" gradientTransform="scale(1.49989 .58672)rotate(-90 17.875 8)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="k8h58xbij"/><stop offset="1" class="zr_1s_bhg"/></radialGradient><radialGradient id="iWrix3d" cx="0" cy="0" r="1" gradientTransform="rotate(-57.512 22.14 -3.79)scale(.81257 2.98595)" gradientUnits="userSpaceOnUse"><stop class="n8501tb7h"/><stop offset=".615" class="t0gw48b3i"/></radialGradient><radialGradient id="iTIY5Qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03773 -1.22791 0 17.314 12.48)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="mrtz5_gxn"/><stop offset="1" class="um4p__bni"/></radialGradient><radialGradient id="icmYJFc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 11.512 1.92)scale(.43456 .59827)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTecODJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03779 -1.22797 0 12.301 12.48)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="mrtz5_gxn"/><stop offset="1" class="um4p__bni"/></radialGradient><radialGradient id="iFbcshM" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.064 .28)scale(.56764 .68234)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRhuwwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 .74219 -.13122 -.03315 21.407 11.326)" gradientUnits="userSpaceOnUse"><stop class="alegm0bhy"/><stop offset="1" class="p_nkfzbsb"/></radialGradient><radialGradient id="irLEf8c" cx="0" cy="0" r="1" gradientTransform="matrix(-.77386 .0032 -.00524 -1.2664 8.844 11.57)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="ascgmfalu"/><stop offset=".687" class="o301vhxpn"/></radialGradient><radialGradient id="i8gh6Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.094)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><radialGradient id="iBfj5Pd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.125)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="ieAjMmb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.078)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iTUCPGc" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.61)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><linearGradient id="iOhOn5b" x1="6.988" x2="7.195" y1="29.407" y2="29.407" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="iAomAlC" x1="16.932" x2="14.847" y1="28.546" y2="28.12" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="im9eHqM" x1="13.726" x2="14.226" y1="26.766" y2="26.813" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="iTudamq" x1="16.414" x2="15.153" y1="29.07" y2="29.123" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="itSm4AK" x1="11.675" x2="12.612" y1="21.65" y2="21.469" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iC6TSsc" x1="18.074" x2="17.137" y1="21.65" y2="21.469" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iimzjsu" x1="12.219" x2="9.392" y1="26.17" y2="26.807" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="iwOdF4c" x1="9.392" x2="11.085" y1="16.977" y2="22.375" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="i2jMWwb" x1="12.268" x2="12.268" y1="29.922" y2="24.7" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="i1VflDU" x1="18.023" x2="21.304" y1="29.125" y2="16.977" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iEAfnnc" x1="17" x2="17.152" y1="26.539" y2="26.571" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iz2Begd" x1="26.981" x2="24.992" y1="21.782" y2="21.782" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iWBccNc" x1="26.336" x2="26.336" y1="25.469" y2="22.563" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="iIrRcKb" x1="28.179" x2="23.367" y1="14.344" y2="19.782" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="i8X5aed" x1="27.914" x2="23.989" y1="27.807" y2="27.807" gradientUnits="userSpaceOnUse"><stop class="g5msifdtf"/><stop offset=".951" class="sd-vlpefb"/></linearGradient><linearGradient id="ivKkQAc" x1="28.653" x2="26.026" y1="28.118" y2="28.118" gradientUnits="userSpaceOnUse"><stop class="x0n4s-bkb"/><stop offset="1" class="runotir-h"/></linearGradient><linearGradient id="iep2WYd" x1="23.699" x2="25.565" y1="25.609" y2="25.609" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i0UPD0b" x1="23.614" x2="25.48" y1="27.034" y2="27.034" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iaOTrJt" x1="23.699" x2="25.565" y1="28.458" y2="28.458" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iT5Gk9b" x1="15.786" x2="15.049" y1="13.838" y2="13.994" gradientUnits="userSpaceOnUse"><stop class="h60g8cpla"/><stop offset="1" class="jfjeh5bbx"/></linearGradient><linearGradient id="iTbGMGd" x1="14.811" x2="14.949" y1="12.04" y2="13.58" gradientUnits="userSpaceOnUse"><stop class="hcyfg3vll"/><stop offset="1" class="o4qkhev5k"/></linearGradient><linearGradient id="iE5JQae" x1="18.208" x2="17.848" y1="12.158" y2="12.38" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iN3jgZV" x1="13.156" x2="12.795" y1="12.158" y2="12.38" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6dlANQ" x1="21.212" x2="20.677" y1="11.586" y2="11.61" gradientUnits="userSpaceOnUse"><stop class="bookipbew"/><stop offset="1" class="vo-fv2-ue"/></linearGradient><linearGradient id="iodu1md" x1="23.304" x2="6.367" y1="9.438" y2="9.753" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="iAJlZRd" x1="8.554" x2="9.992" y1="6.877" y2="7.063" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="iLKj4pc" x1="15.461" x2="15.461" y1="7.93" y2="7.727" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="iAYhuWd" x1="15.507" x2="15.507" y1="5.848" y2="5.985" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><filter id="iFowyve" width="7.346" height="5.139" x="11.201" y="19.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".25"/></filter><filter id="idysBLQ" width="3.106" height="2.966" x="13.406" y="21.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/></filter><filter id="izDQT8w" width="8.299" height="13.046" x="5.292" y="16.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/></filter><filter id="iJvFfPc" width="8.299" height="13.046" x="16.153" y="16.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/></filter><filter id="isKG75X" width="6.656" height="6.656" x="22.367" y="13.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".125"/></filter><filter id="iG5WOSW" width="7.206" height="7.206" x="22.067" y="13.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/></filter><filter id="iqDUSDd" width="5.327" height="6.052" x="23.131" y="23.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.52549 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/></filter><filter id="iZYVphe" width="2.262" height=".3" x="23.549" y="25.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".05"/></filter><filter id="ioiF0Cc" width="2.262" height=".3" x="23.464" y="26.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".05"/></filter><filter id="ik0Z38d" width="2.262" height=".3" x="23.549" y="28.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".05"/></filter><filter id="iijjmtd" width="3.936" height="3.836" x="7.437" y="10.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.654902 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/></filter><filter id="i0Odijm" width="2.786" height="2.786" x="7.962" y="11.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".125"/></filter><filter id="ipSU0Zd" width="3.886" height="3.886" x="18.318" y="10.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.780392 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/></filter><filter id="i8zzRRb" width="2.786" height="2.786" x="18.893" y="11.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".125"/></filter><filter id="i06l8Yd" width="12.719" height="13.82" x="8.884" y="6.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.666667 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/></filter><filter id="i17Wffb" width="3.022" height="4.081" x="13.025" y="11.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".25"/></filter><filter id="iGkbqsd" width="2.656" height="3.581" x="13.483" y="12.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.545098 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/><feGaussianBlur result="effect2_foregroundBlur_4002_2764" stdDeviation=".125"/></filter><filter id="i787x9c" width="2.656" height="3.581" x="13.483" y="11.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".125"/></filter><filter id="iFmji1b" width="4.097" height="1.632" x="12.762" y="15.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".05"/></filter><filter id="ifgUYqb" width=".874" height=".77" x="16.486" y="11.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".05"/></filter><filter id="i9Asvhc" width=".964" height=".99" x="17.466" y="11.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".1"/></filter><filter id="iLjMXUb" width="1.074" height="1.135" x="12.362" y="11.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".1"/></filter><filter id="ipwekXd" width="1.019" height=".78" x="11.48" y="11.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2764" stdDeviation=".05"/></filter><filter id="iUMVclc" width="12.369" height="3.947" x="8.798" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/></filter><filter id="iSSqK7b" width="19.912" height="4.003" x="4.916" y="7.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2764"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2764" result="effect2_innerShadow_4002_2764"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-detective-light" /></template>
<style>
.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.aknm_exmg {
  stop-color: var(--svg-color--ce9381, #CE9381);
}

.alegm0bhy {
  stop-color: var(--svg-color--494848, #494848);
}

.altutfb8x {
  stop-color: var(--svg-color--ab9ca0, #AB9CA0);
}

.arpepeb0z {
  stop-color: var(--svg-color--665c8a, #665C8A);
}

.ascgmfalu {
  stop-color: var(--svg-color--140b1a, #140B1A);
}

.asvjbc-zd {
  stop-color: var(--svg-color--b4366c, #B4366C);
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bc2ld5biv {
  stop-color: var(--svg-color--46446d, #46446D);
}

.bc7i0ongh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.7 28.38h1.96");
}

.bcp6zybsw {
  stop-color: var(--svg-color--7c707d, #7C707D);
}

.bgcqg98jc {
  fill: var(--svg-color--c9928a, #C9928A);
  d: path("m14.495 12.81l-.943 1.952c-.117.402.164.804.56.804h.848c.397 0 .678-.408.56-.804l-.572-1.953c-.123-.432-.325-.432-.453 0");
}

.bookipbew {
  stop-color: var(--svg-color--343233, #343233);
}

.bpzzcwljp {
  stop-color: var(--svg-color--5b537a, #5B537A);
}

.bslse1b3i {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
}

.bt46k-bry {
  stop-color: var(--svg-color--810937, #810937);
}

.by194g1ei {
  d: path("M22.727 29.922h4.296a12.16 12.16 0 0 0-4.296-8.538z");
}

.c_gtmdbzk {
  stop-color: var(--svg-color--5e5775, #5E5775);
}

.c07mg7bed {
  stop-color: var(--svg-color--e0b2a7, #E0B2A7);
  stop-opacity: 0;
}

.c1vbzi-sh {
  stop-color: var(--svg-color--f3c3b1, #F3C3B1);
}

.c77y5fbir {
  stop-color: var(--svg-color--574069, #574069);
}

.cj2gegbdf {
  stop-color: var(--svg-color--4f4376, #4F4376);
}

.cjc9cqblk {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crspr0bkb {
  stop-color: var(--svg-color--b78379, #B78379);
  stop-opacity: 0;
}

.cw4t4r-fb {
  stop-color: var(--svg-color--c99293, #C99293);
}

.cw9lwsb0z {
  stop-color: var(--svg-color--4f4376, #4F4376);
  stop-opacity: 0;
}

.d-k16gi6m {
  stop-color: var(--svg-color--b6376a, #B6376A);
  stop-opacity: 0;
}

.d1xnqxb5m {
  stop-color: var(--svg-color--573a60, #573A60);
  stop-opacity: 0;
}

.damj_nbgh {
  stop-color: var(--svg-color--7577a1, #7577A1);
}

.dmg57hbhe {
  stop-color: var(--svg-color--c99293, #C99293);
  stop-opacity: 0;
}

.dnfp-euku {
  d: path("M8.126 7.748a.1.1 0 0 0 .095.131h13.287a.1.1 0 0 0 .094-.132l-.192-.56l-.429-1.244a.1.1 0 0 0-.094-.068H8.829a.1.1 0 0 0-.095.068c-.19.554-.38 1.12-.531 1.575z");
}

.dv70acbut {
  stop-color: var(--svg-color--534971, #534971);
  stop-opacity: 0;
}

.dvhbibcqh {
  stop-color: var(--svg-color--625783, #625783);
}

.e1av8fbyb {
  d: path("M17.317 11.548a1.025 1.025 0 0 1 .988 1.295h-1.98a1.03 1.03 0 0 1 .992-1.295");
}

.e6z7sjb6l {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
}

.e9sv_2buc {
  stop-color: var(--svg-color--dbc8d7, #DBC8D7);
}

.ee70-8_hv {
  stop-color: var(--svg-color--eab59c, #EAB59C);
}

.em148031i {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.294l-2.281 10.862z");
}

.erhkeibcy {
  width: 2.572px;
  height: 5.438px;
  x: 24.409px;
  y: 20.227px;
  rx: 1.286px;
}

.f-gl8-mln {
  d: path("M18.23 12.438a.97.97 0 0 0-.266-.532l-.298.328l.134.262z");
}

.f-jevn7df {
  stop-color: var(--svg-color--ffdfc5, #FFDFC5);
  stop-opacity: 0;
}

.f87czphzs {
  stop-color: var(--svg-color--5b4361, #5B4361);
}

.f9qu94gfh {
  stop-color: var(--svg-color--b4807f, #B4807F);
  stop-opacity: 0;
}

.fce7k9bpt {
  stop-color: var(--svg-color--d4a293, #D4A293);
}

.fchl8077b {
  stop-color: var(--svg-color--4e4270, #4E4270);
}

.fisd__bqs {
  stop-color: var(--svg-color--ce3657, #CE3657);
}

.fjaxvnbiy {
  stop-color: var(--svg-color--4c3156, #4C3156);
  stop-opacity: 0;
}

.fk1gregde {
  stop-color: var(--svg-color--57497f, #57497F);
  stop-opacity: 0;
}

.fkavrburz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.7 25.531h1.96");
}

.fldt-ebmj {
  fill: var(--svg-color--89024f, #89024F);
  d: path("M14.81 16.4c-.582 0-1.13-.137-1.59-.377c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.819.972c.764 0 1.434-.389 1.819-.972c.099-.149-.07-.32-.228-.24a3.4 3.4 0 0 1-1.591.377");
}

.foejprbbc {
  stop-color: var(--svg-color--767290, #767290);
}

.fpxhxfble {
  stop-color: var(--svg-color--5c4b6c, #5C4B6C);
}

.ft5dv1b6b {
  fill: none;
}

.fwxdqq60h {
  stop-color: var(--svg-color--fbc4a9, #FBC4A9);
}

.g1ovp4bwp {
  fill-rule: evenodd;
  d: path("M25.695 20.672a3.578 3.578 0 1 0 0-7.156a3.578 3.578 0 0 0 0 7.156m0-.593a2.984 2.984 0 1 0 0-5.969a2.984 2.984 0 0 0 0 5.969");
}

.g5msifdtf {
  stop-color: var(--svg-color--ffdec2, #FFDEC2);
}

.g7gmqhncd {
  d: path("M7.023 29.922H2.727a12.16 12.16 0 0 1 4.296-8.538z");
}

.gemgotgww {
  d: path("m14.098 24.35l-.692-1.334l1.453-1.351l1.453 1.351l-.662 1.331a.15.15 0 0 1-.134.083h-1.285a.15.15 0 0 1-.133-.08");
}

.ghq__ebhv {
  d: path("M17.242 11.765c.072.097-.08.216-.254.346c-.173.13-.302.221-.375.123c-.073-.097.008-.282.182-.411c.173-.13.373-.156.446-.059");
}

.gi2uz_g9v {
  stop-color: var(--svg-color--514c59, #514C59);
}

.gn4fmf85p {
  stop-color: var(--svg-color--3e3058, #3E3058);
  stop-opacity: 0;
}

.gtmei0bfc {
  stop-color: var(--svg-color--b77e85, #B77E85);
  stop-opacity: 0;
}

.h60g8cpla {
  stop-color: var(--svg-color--e1b2a5, #E1B2A5);
}

.hb-nqccyv {
  stop-color: var(--svg-color--b77e85, #B77E85);
}

.hcyfg3vll {
  stop-color: var(--svg-color--b48080, #B48080);
}

.hknh16mic {
  d: path("M8.951 11.976c-.03-.36-.067-1.388-.067-1.652c0-.307.124-.674.37-.858l.185-.184c.308-.245.432-.613.432-.98V7.32c0-.307.184-.552.493-.613c.74-.184 2.28-.49 4.499-.49s3.76.306 4.499.49c.246.061.493.306.493.613v.98c0 .368.185.736.431.98c.577.405.541.627.493 1.104c-.014.148-.061 1.372-.102 1.654l-.305 4.549c-.185 2.033-1.783 3.45-3.69 3.45h-3.688c-1.967 0-3.504-1.417-3.689-3.45z");
}

.hqp1wu_he {
  cx: 20.286px;
  cy: 12.68px;
  r: 1.143px;
}

.i0-8psn3d {
  fill: var(--svg-color--cd9b90, #CD9B90);
  d: path("m14.372 12.622l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.433-.742-.433-.88 0");
}

.i78i3vbiy {
  stop-color: var(--svg-color--ad254b, #AD254B);
}

.i7g4iz6bw {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
  stop-opacity: 0;
}

.icczjvbzw {
  stop-color: var(--svg-color--f2c5ac, #F2C5AC);
}

.ig92uxq3u {
  stop-color: var(--svg-color--50d5fa, #50D5FA);
}

.ijrk-tbbt {
  d: path("m8.07 10.762l.198.814c.058.35.357.6.701.624c-.014-.226-.046-.631-.058-.978l-.017-.46z");
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.ivj3pk5jv {
  d: path("M8.803 5.743a.1.1 0 0 0 .095.132h11.92a.1.1 0 0 0 .094-.133a87 87 0 0 0-.639-1.789c-.469-1.25-1.637-1.875-2.297-1.875c-.735-.016-1.259.318-1.65.567l-.194.12c-.578.344-.808.4-1.277.4c-.371 0-.762-.15-1.184-.368q-.11-.058-.247-.142c-.436-.26-1.078-.642-1.905-.526c-.956.134-1.66.93-2.097 1.945a29 29 0 0 0-.619 1.669");
}

.j_dulcbnt {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.554 2.727 29.923");
}

.j-ut2xl5o {
  d: path("M12.625 19.547c.026.292.262.988.999 1.438c.736.45 1.14.63 1.25.664c.11-.034.515-.214 1.251-.664c.737-.45.973-1.146 1-1.438z");
}

.j05e95eeg {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
}

.j0dv9ngke {
  stop-color: var(--svg-color--cb8b78, #CB8B78);
}

.j11nupb8y {
  stop-color: var(--svg-color--696284, #696284);
}

.j3zeyq-sj {
  stop-color: var(--svg-color--cb8b77, #CB8B77);
}

.jfjeh5bbx {
  stop-color: var(--svg-color--e1b2a5, #E1B2A5);
  stop-opacity: 0;
}

.jpbxw370c {
  d: path("M6.386 7.879c-.26-.016-.991.034-1.316.36c-.358.357-.055 1.073.508 1.652c.539.554 2.335 1.738 5.18 1.738h8.167c2.873 0 4.689-1.184 5.234-1.738c.568-.58.874-1.295.513-1.653c-.328-.325-1.067-.375-1.33-.359z");
}

.js34-kdjw {
  stop-color: var(--svg-color--dbafa2, #DBAFA2);
}

.k1zgefb2d {
  stop-color: var(--svg-color--605a74, #605A74);
}

.k5i52n_gm {
  stop-color: var(--svg-color--2683c8, #2683C8);
}

.k7e504bil {
  cx: 25.695px;
  cy: 17.094px;
  r: 3.078px;
  fill: var(--svg-color--3e2657, #3E2657);
}

.k8h58xbij {
  stop-color: var(--svg-color--cd9794, #CD9794);
}

.k9h8bsbwk {
  stop-color: var(--svg-color--403357, #403357);
}

.kbjnrqkvo {
  stop-color: var(--svg-color--d3a18f, #D3A18F);
  stop-opacity: 0;
}

.kdvr4u58b {
  d: path("m14.372 12.364l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.433-.742-.433-.88 0");
}

.kdzxr8bcy {
  d: path("m20.76 10.762l-.02.389c-.018.345-.04.777-.063 1.1c.358-.01.597-.252.657-.613l.23-.876z");
}

.kpssiabxl {
  stop-color: var(--svg-color--5c5178, #5C5178);
  stop-opacity: 0;
}

.kqcubybll {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.81 16.4c-.582 0-1.13-.137-1.59-.377c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.819.972c.764 0 1.434-.389 1.819-.972c.099-.149-.07-.32-.228-.24a3.4 3.4 0 0 1-1.591.377Z");
}

.kte-0sm3k {
  stop-color: var(--svg-color--cfbdc9, #CFBDC9);
  stop-opacity: 0;
}

.kvzrrwynu {
  stop-color: var(--svg-color--6a5e90, #6A5E90);
}

.l50s_ac3p {
  stop-color: var(--svg-color--b3827d, #B3827D);
}

.l9k3lrq7u {
  stop-color: var(--svg-color--d1c0d6, #D1C0D6);
}

.la8vvmbhh {
  stop-color: var(--svg-color--ad254b, #AD254B);
  stop-opacity: 0;
}

.lcqew7b7f {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
  stop-opacity: 0;
}

.lcv6zvemz {
  stop-color: var(--svg-color--f5cbb4, #F5CBB4);
  stop-opacity: 0;
}

.ld92_g1my {
  stop-color: var(--svg-color--7f81b2, #7F81B2);
}

.lg14abbip {
  stop-color: var(--svg-color--605a74, #605A74);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljhgv1b3v {
  cx: 11.99px;
  cy: 11.986px;
  rx: 0.448px;
  ry: 0.227px;
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.mh39h7hpm {
  cx: 9.356px;
  cy: 12.68px;
  r: 1.918px;
}

.mibx7d57r {
  fill: var(--svg-color--000, #000);
  d: path("M12.886 12.573a.585.585 0 0 0-.587-.587a.585.585 0 0 0-.522.857h1.04a.6.6 0 0 0 .07-.27");
}

.mop_zlbnl {
  d: path("m10.75 16.977l2.742 12.945h-1.797a1566 1566 0 0 1-4.625-7.734c-.422-.735-.219-.906-.14-1.031c.077-.125.374-.36.671-.47c.238-.087.328-.202.344-.25c.057-.067.069-.3-.344-.687c-.412-.387-1.307-1.067-1.703-1.36c-.234-.187-.652-.608-.602-.983s.652-.435.766-.43z");
}

.mrtz5_gxn {
  stop-color: var(--svg-color--5a3c37, #5A3C37);
}

.mw9gk7bly {
  stop-color: var(--svg-color--3f3050, #3F3050);
}

.mx64gfpes {
  stop-color: var(--svg-color--6a6385, #6A6385);
}

.n0h_63bcp {
  cx: 20.286px;
  cy: 12.68px;
  r: 1.918px;
}

.n3m4ul9nu {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.555 11.235c.75 0 1.384.518 1.556 1.217a.315.315 0 0 1-.308.391h-2.562a.264.264 0 0 1-.261-.312a1.606 1.606 0 0 1 1.575-1.296");
}

.n3pyssb7u {
  stop-color: var(--svg-color--452053, #452053);
}

.n6k7cjgpd {
  stop-color: var(--svg-color--cd8e7f, #CD8E7F);
}

.n8501tb7h {
  stop-color: var(--svg-color--d4a1a0, #D4A1A0);
}

.nf2o-hpjm {
  stop-color: var(--svg-color--857da2, #857DA2);
}

.ng-28zxwb {
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.554 2.727 29.923");
}

.nig76no1i {
  stop-color: var(--svg-color--4e4270, #4E4270);
  stop-opacity: 0;
}

.njrd_tayg {
  stop-color: var(--svg-color--573a60, #573A60);
}

.nw6o4wclj {
  stop-color: var(--svg-color--624c7f, #624C7F);
}

.nzffxlbem {
  stop-color: var(--svg-color--4f456a, #4F456A);
}

.o-88nes6c {
  stop-color: var(--svg-color--e8b198, #E8B198);
}

.o301vhxpn {
  stop-color: var(--svg-color--494645, #494645);
}

.o4qkhev5k {
  stop-color: var(--svg-color--b48080, #B48080);
  stop-opacity: 0;
}

.o58_qgbus {
  stop-color: var(--svg-color--dcc8d0, #DCC8D0);
}

.o8gobxb3n {
  stop-color: var(--svg-color--897b8e, #897B8E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.onow8rbko {
  stop-color: var(--svg-color--f2c5ac, #F2C5AC);
  stop-opacity: 0;
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.p_nkfzbsb {
  stop-color: var(--svg-color--494848, #494848);
  stop-opacity: 0;
}

.p12q4lqjb {
  stop-color: var(--svg-color--ca968f, #CA968F);
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pwa97nbfq {
  stop-color: var(--svg-color--5b4361, #5B4361);
  stop-opacity: 0;
}

.pxopwiwar {
  stop-color: var(--svg-color--c18e76, #C18E76);
  stop-opacity: 0;
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
  stop-opacity: 0;
}

.q8ppcjbus {
  stop-color: var(--svg-color--624c7f, #624C7F);
  stop-opacity: 0;
}

.qasiqcczj {
  stop-color: var(--svg-color--837a8e, #837A8E);
  stop-opacity: 0;
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.rhxl5gb9p {
  d: path("M27.203 22.329c.58 0 1.055.475 1.055 1.055v2.418h-2.111v-2.418c.01-.58.475-1.055 1.056-1.055");
}

.rrgrst12i {
  fill: var(--svg-color--000, #000);
  d: path("M16.73 12.573c0-.326.26-.587.587-.587a.585.585 0 0 1 .522.857h-1.04a.53.53 0 0 1-.07-.27");
}

.runotir-h {
  stop-color: var(--svg-color--ffdfbf, #FFDFBF);
  stop-opacity: 0;
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.s0-op-jbm {
  d: path("m17.77 22.747l.814-3.778h-1.852l-1.867 2.485v.437l1.96 1.781c.097.084.327.214.477.07c.15-.143.35-.484.467-.995");
}

.sd-vlpefb {
  stop-color: var(--svg-color--daa59b, #DAA59B);
}

.sn5q5zbjv {
  stop-color: var(--svg-color--eda886, #EDA886);
}

.sxgpvtb4k {
  d: path("m14.372 12.622l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.433-.742-.433-.88 0");
}

.t-s_cxb3y {
  stop-color: var(--svg-color--5b4373, #5B4373);
}

.t0gw48b3i {
  stop-color: var(--svg-color--d4a1a0, #D4A1A0);
  stop-opacity: 0;
}

.t0ozsbnai {
  stop-color: var(--svg-color--766c87, #766C87);
}

.t11-a9gub {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
  stop-opacity: 0;
}

.thvbr9biq {
  stop-color: var(--svg-color--27a8e3, #27A8E3);
}

.tjiypub2l {
  width: 1.769px;
  height: 2.205px;
  x: 25.512px;
  y: 15.977px;
  rx: 0.885px;
}

.tkuxygb0m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.242 11.765c.072.097-.08.216-.254.346c-.173.13-.302.221-.375.123c-.073-.097.008-.282.182-.411c.173-.13.373-.156.446-.059");
}

.tnc_xbdtt {
  stop-color: var(--svg-color--202d61, #202D61);
}

.tnef9wrdf {
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.294l-2.281 10.862z");
}

.tnviirb6b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.614 26.956h1.962");
}

.tvwclb40x {
  stop-color: var(--svg-color--d3a18f, #D3A18F);
}

.ug62x2bvv {
  stop-color: var(--svg-color--d4a293, #D4A293);
  stop-opacity: 0;
}

.um4p__bni {
  stop-color: var(--svg-color--442e33, #442E33);
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v6_19y23u {
  stop-color: var(--svg-color--e0b2a7, #E0B2A7);
}

.v9c6zoseo {
  d: path("M13.236 12.452c0-.33-.27-.552-.343-.618l-.33.32l.203.415z");
}

.vd-u4acdq {
  cx: 25.695px;
  cy: 17.094px;
  r: 2.984px;
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vo-fv2-ue {
  stop-color: var(--svg-color--100917, #100917);
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.vz-bod6vj {
  stop-color: var(--svg-color--b78379, #B78379);
}

.w5xgflzkx {
  stop-color: var(--svg-color--b4807f, #B4807F);
}

.wa3u08nda {
  stop-color: var(--svg-color--ffdfc5, #FFDFC5);
}

.wibdzhbon {
  d: path("m11.972 22.727l-.806-3.758h1.851l1.867 2.488v.434l-1.96 1.781c-.097.084-.327.214-.477.07c-.15-.143-.357-.503-.475-1.015");
}

.ws-9x4b9n {
  d: path("M23.132 24.82c0-.439.355-.8.793-.8h3.023c.724 0 1.31.587 1.31 1.31v3.5a1.09 1.09 0 0 1-1.091 1.092h-3.242a.798.798 0 0 1-.349-1.516a.802.802 0 0 1 0-1.435a.802.802 0 0 1 0-1.434a.8.8 0 0 1-.445-.718");
}

.wss6y3b2p {
  stop-color: var(--svg-color--b41945, #B41945);
}

.x__1z6aoh {
  stop-color: var(--svg-color--39304b, #39304B);
}

.x0n4s-bkb {
  stop-color: var(--svg-color--ffdfbf, #FFDFBF);
}

.x26s0_r_n {
  stop-color: var(--svg-color--443665, #443665);
}

.x2herp8_d {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
  stop-opacity: 0;
}

.x84cwhbna {
  stop-color: var(--svg-color--57497f, #57497F);
}

.x8vyagemg {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.061 11.235c-.75 0-1.384.518-1.556 1.217c-.052.2.102.391.307.391h2.563a.264.264 0 0 0 .261-.312a1.61 1.61 0 0 0-1.575-1.296");
}

.xhfhhvoed {
  d: path("m18.996 16.977l-2.743 12.945h1.797c1.401-2.333 4.288-7.147 4.625-7.734c.422-.735.219-.906.14-1.031c-.077-.125-.374-.36-.671-.47c-.238-.087-.328-.202-.344-.25c-.057-.067-.069-.3.344-.687c.412-.387 1.307-1.067 1.703-1.36c.234-.187.652-.608.602-.983s-.651-.435-.766-.43z");
}

.xp457mbaj {
  stop-color: var(--svg-color--bd858b, #BD858B);
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.y__sil0st {
  stop-color: var(--svg-color--f5cbb4, #F5CBB4);
}

.y_qlpp2fu {
  d: path("M12.3 11.548a1.025 1.025 0 0 0-.989 1.295h1.98a1 1 0 0 0 .038-.27a1.03 1.03 0 0 0-1.03-1.025");
}

.y-v21bc8n {
  cx: 11.99px;
  cy: 11.986px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.448px;
  ry: 0.227px;
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yxzzhscvi {
  cx: 20.286px;
  cy: 12.68px;
  r: 1.918px;
  fill: var(--svg-color--ebbca7, #EBBCA7);
}

.yyxxh9qfh {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.747l.814-3.778h-1.852l-1.867 2.485v.437l1.96 1.781c.097.084.327.214.477.07c.15-.143.35-.484.467-.995");
}

.yzf80p4jc {
  cx: 9.356px;
  cy: 12.68px;
  r: 1.143px;
}

.z_czc81-p {
  fill: var(--svg-color--927d95, #927D95);
  d: path("m11.701 19.668l.69 3.215c.1.438.278.746.407.869s.325.011.407-.06l1.67-1.517l1.669 1.517c.082.071.28.183.408.06s.299-.415.4-.852l.696-3.232h-1.584l-1.59 2.116l-1.588-2.116z");
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z_rbfc5vy {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
}

.zglqorbou {
  stop-color: var(--svg-color--aa717e, #AA717E);
}

.zknvtjbtz {
  stop-color: var(--svg-color--c58c92, #C58C92);
  stop-opacity: 0;
}

.zpb-61ddc {
  stop-color: var(--svg-color--645d7e, #645D7E);
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

.zr_1s_bhg {
  stop-color: var(--svg-color--cd9794, #CD9794);
  stop-opacity: 0;
}

.zswbabceh {
  d: path("m13.289 29.922l.854-5.407a.1.1 0 0 1 .098-.085h1.247a.1.1 0 0 1 .099.085l.827 5.407z");
}

.zuvzebcmo {
  stop-color: var(--svg-color--4c3156, #4C3156);
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

</style>
