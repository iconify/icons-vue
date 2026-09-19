<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iEiXAlc)"><path fill="url(#iJpod9c)" clip-rule="evenodd" class="is335clhe"/><path fill="url(#iiGjhDc)" clip-rule="evenodd" class="is335clhe"/><path fill="url(#izllg3c)" clip-rule="evenodd" class="is335clhe"/><path fill="url(#iQaDKIc)" clip-rule="evenodd" class="is335clhe"/><path fill="url(#iUfRxOb)" clip-rule="evenodd" class="is335clhe"/><path fill="url(#iLtFeQd)" clip-rule="evenodd" class="is335clhe"/><path fill="url(#igWfARV)" clip-rule="evenodd" class="is335clhe"/><path fill="url(#isaHjae)" clip-rule="evenodd" class="is335clhe"/><path fill="url(#iqWizde)" clip-rule="evenodd" class="is335clhe"/><path fill="url(#iFKsCwe)" clip-rule="evenodd" class="is335clhe"/></g><path fill="url(#iRWKA8b)" clip-rule="evenodd" class="is335clhe"/><g filter="url(#iu5Kveb)"><path class="l1fr7gb1j"/><path fill="url(#icpvgWn)" class="tv3x8ynxn"/></g><path fill="url(#ikhzZjb)" class="enrfq8h_k"/><path fill="url(#iCpsSzd)" class="enrfq8h_k"/><path fill="url(#iMBtvie)" class="ouo32abns"/><path fill="url(#iEYjmre)" class="ouo32abns"/><path fill="url(#izYYXoc)" class="lsuuu0h2r"/><path fill="url(#icNoVrb)" class="p4y5efbno"/><path fill="url(#iUNJ9Gd)" class="p4y5efbno"/><path fill="url(#ikBOvzL)" class="p4y5efbno"/><path fill="url(#i5bz60d)" class="p4y5efbno"/><path fill="url(#i4OAhLd)" class="lqgbnzbne"/><path fill="url(#iVyMdve)" class="lqgbnzbne"/><path fill="url(#iao7sVb)" class="lqgbnzbne"/><path fill="url(#ip4B8ge)" class="hbbomwb3k"/><path fill="url(#ijnUkye)" class="hbbomwb3k"/><path fill="url(#iwZ3oHI)" class="qyoz56odi"/><path fill="url(#ioUWG3b)" class="qyoz56odi"/><path fill="url(#iurx9Ld)" class="qyoz56odi"/><path fill="url(#ipS32hb)" class="yow4o5baa"/><path fill="url(#iQJIpvw)" class="yow4o5baa"/><path fill="url(#iZDSDze)" class="yow4o5baa"/><path fill="url(#i8gzboc)" class="yow4o5baa"/><path fill="url(#i9GooBe)" class="yow4o5baa"/><path fill="url(#iuUuJxc)" class="o7wsyd3ap"/><path fill="url(#iY73QDc)" class="o7wsyd3ap"/><path fill="url(#idbwerS)" class="qw9ryka9f"/><path fill="url(#iXtfGwG)" class="qw9ryka9f"/><path fill="url(#iX0m7be)" class="qw9ryka9f"/><path fill="url(#iNJhqie)" class="qw9ryka9f"/><g filter="url(#iVkNXCd)"><path fill="url(#ijlSSJc)" class="hvtkrgbbt"/><path fill="url(#i97lfPh)" class="hvtkrgbbt"/><path fill="url(#ifZKqEc)" class="hvtkrgbbt"/></g><path fill="url(#i8pN00b)" class="q2ut5cc4l"/><path fill="url(#iAnmTXx)" class="q2ut5cc4l"/><path fill="url(#i6YDFhE)" class="q2ut5cc4l"/><g filter="url(#i4uclnb)"><path fill="url(#i9wInkM)" class="kgods_8bf"/></g><g filter="url(#iPJiENy)"><path fill="url(#icAvcDc)" class="gdjntuneq"/><path fill="url(#iCOepKe)" class="gdjntuneq"/><path fill="url(#ihqvokc)" class="gdjntuneq"/><path fill="url(#iqtC2fA)" class="gdjntuneq"/><path fill="url(#i29t2sb)" class="gdjntuneq"/></g><g filter="url(#iWqMCDb)"><path stroke="url(#iK4bu1c)" class="o2w9f1bnl"/></g><g filter="url(#iDh3Gnb)"><path stroke="url(#iUhOFDT)" class="sezmncb3p"/></g><g filter="url(#iZGbCyd)"><path stroke="url(#iB87UDg)" class="exrdolbwt"/></g><g filter="url(#itmb0Mb)"><path fill="url(#iRTZr8d)" class="v-reotlad"/></g><g filter="url(#iXQVoGc)"><path fill="url(#i4qOaJe)" class="rj47jswmc"/></g><g filter="url(#iE19PYC)"><path class="jjpsrbe0r"/><path fill="url(#io1Ypjc)" class="ibnsaxbhm"/></g><g filter="url(#iJJpEPe)"><path class="jp31o1b_h"/><path fill="url(#i0YJxqd)" class="qln77wdhf"/></g><g filter="url(#ibZCRYb)"><path fill="url(#ief4m0U)" class="i78ylcbrm"/><path fill="url(#irx1anN)" class="i78ylcbrm"/><path fill="url(#iLRMhgf)" class="i78ylcbrm"/><path fill="url(#icPUDCl)" class="i78ylcbrm"/><path fill="url(#iwbzo5a)" class="i78ylcbrm"/><path fill="url(#i1e8Rze)" class="i78ylcbrm"/><path fill="url(#iZObare)" class="i78ylcbrm"/></g><path fill="url(#iT9tB0c)" class="i78ylcbrm"/><path fill="url(#ivVFlCe)" clip-rule="evenodd" class="omp7-5b0i"/><path fill="url(#iGtB32b)" clip-rule="evenodd" class="omp7-5b0i"/><g filter="url(#i7VANVj)"><path class="l4mrzh3bf"/></g><g filter="url(#iKS8twd)"><path fill="url(#iWrfjce)" class="i7z7cdbov"/><path fill="url(#ipVVvpF)" class="i7z7cdbov"/><path fill="url(#ik249zd)" class="i7z7cdbov"/><path fill="url(#icANAvb)" class="i7z7cdbov"/></g><path fill="url(#iTYQo2b)" class="i7z7cdbov"/><path fill="url(#igVlJAA)" class="i7z7cdbov"/><g filter="url(#iVTdgWb)"><path stroke="url(#iYs8s7G)" class="zsjn6kjhx"/></g><path class="rssb04bxd"/><g filter="url(#iOWplPe)"><path class="bvnc75b9w"/></g><g filter="url(#ipxnzmd)"><path class="dvc58kbnt"/></g><g filter="url(#i86aMrd)"><path class="uv8wvy1nd"/></g><g filter="url(#i8UbPGe)"><path clip-rule="evenodd" class="sf7ql_tih"/></g><path class="nvzbckocx"/><path fill="url(#i6DS8Zb)" class="ur6jocr6m"/><path class="wv0s8obst"/><g filter="url(#iCOPapc)"><path class="mtg46-bqu"/><path fill="url(#iSdfRTm)" class="x2b-z-btr"/></g><g filter="url(#i5osuLe)"><path fill="url(#iXLbM1d)" class="hr8ud0h9b"/></g><path class="dl98_lb6u"/><path fill="url(#iALN5Jc)" class="kadpdpbne"/><path class="pklbb-bat"/><g filter="url(#iVa13lc)"><path fill="url(#ici52Bb)" class="j6kqqqjso"/></g><g filter="url(#i5epZoe)"><ellipse transform="rotate(-27.914 12.757 11.83)" class="gtj5jfb3o"/><ellipse fill="url(#iSl88ze)" transform="rotate(-27.914 12.757 11.83)" class="bwu4585sd"/></g><g filter="url(#i3MGpac)"><path class="s5j8b3t1r"/></g><g filter="url(#ibXgVYb)"><path class="j1w5a6hgo"/></g><g filter="url(#iDIWaFb)"><path fill="url(#i1ygJYZ)" class="tod4lrkkn"/><path fill="url(#iLbH6rb)" class="tod4lrkkn"/></g><g filter="url(#iusQLtd)"><path fill="url(#iC5KNzd)" class="bpqpsabpn"/><path fill="url(#iLcrXvb)" class="bpqpsabpn"/><path fill="url(#iq4izgd)" class="bpqpsabpn"/></g><g filter="url(#ijAzVPe)"><path stroke="url(#iJ1SA4b)" class="k5687y9rf"/></g><defs><radialGradient id="iiGjhDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.56158 -2.7482 0 10.59 14.621)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="izllg3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.70241 -5.9401 0 15.268 14.716)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iQaDKIc" cx="0" cy="0" r="1" gradientTransform="rotate(127.617 1.956 8.953)scale(2.0807 2.02025)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iUfRxOb" cx="0" cy="0" r="1" gradientTransform="rotate(100.537 1.112 9.695)scale(2.61721 2.72533)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iLtFeQd" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 1.644 12.35)scale(2.43713 4.64268)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="igWfARV" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 8.983 7.925)scale(1.67575 2.34183)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="isaHjae" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 10.646 7.47)scale(1.96539 4.27643)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iqWizde" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 1.6875 -1.90493 3.24543 18.875 15.938)" gradientUnits="userSpaceOnUse"><stop class="b277vn5kc"/><stop offset="1" class="mbkivbc6y"/></radialGradient><radialGradient id="iFKsCwe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.352 10.107 -2.33)scale(1.40681 .46125)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iRWKA8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.45838 6.45383 0 15.268 18.465)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="dempr2dnp"/><stop offset="1" class="fnokm46vs"/></radialGradient><radialGradient id="ikhzZjb" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.878 26.505)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="iMBtvie" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.442 20.05)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="i5bz60d" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.78125 -1.64554 1.6744 23 21.875)" gradientUnits="userSpaceOnUse"><stop class="apsa9cl1l"/><stop offset="1" class="ji3tmwq8i"/></radialGradient><radialGradient id="iao7sVb" cx="0" cy="0" r="1" gradientTransform="rotate(127.231 1.492 11.592)scale(5.01003 5.42155)" gradientUnits="userSpaceOnUse"><stop offset=".054" class="mi2y_fs0q"/><stop offset="1" class="l1asq8nfe"/></radialGradient><radialGradient id="iwZ3oHI" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.19791 -5.21858 0 15.27 21.692)" gradientUnits="userSpaceOnUse"><stop class="gwxe3pb8f"/><stop offset=".766" class="t0h--bk_d"/></radialGradient><radialGradient id="ioUWG3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.03341 12.2744 0 15.268 25.096)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="d6y68cbbg"/><stop offset=".937" class="e00j6fbsx"/></radialGradient><radialGradient id="ipS32hb" cx="0" cy="0" r="1" gradientTransform="rotate(64.566 -7.347 20.248)scale(2.73433 5.20364)" gradientUnits="userSpaceOnUse"><stop class="it9idqgsx"/><stop offset="1" class="i1mgxs0vi"/></radialGradient><radialGradient id="iQJIpvw" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.21875 -1.03117 0 14.656 18.313)" gradientUnits="userSpaceOnUse"><stop class="cinmdjbay"/><stop offset="1" class="d40ufvb0p"/></radialGradient><radialGradient id="i9GooBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.72434 -4.45555 0 15.268 18.65)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="t9zkmquqg"/><stop offset="1" class="gwxe3pb8f"/></radialGradient><radialGradient id="iuUuJxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.25267 -.93725 1.10778 1.48058 26.974 23.53)" gradientUnits="userSpaceOnUse"><stop class="xcnvxobld"/><stop offset="1" class="k7fvrbbpb"/></radialGradient><radialGradient id="iY73QDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81108 .73899 -.74364 -.8162 28.19 22.115)" gradientUnits="userSpaceOnUse"><stop class="u7id6gble"/><stop offset="1" class="ydn9dmb6d"/></radialGradient><radialGradient id="iXtfGwG" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.26 12.55)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="iX0m7be" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 24.012 16.101)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="iNJhqie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 27.082 17.459)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="i97lfPh" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.677 17.85)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="i9wInkM" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 26.151 21.721)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="iCOepKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62488 2.62025 -2.19236 -1.35953 28.517 23.48)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="ihqvokc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59834 0 0 .51085 23.875 24.989)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="pzho1txaw"/><stop offset="1" class="r-w7u-p-k"/></radialGradient><radialGradient id="iqtC2fA" cx="0" cy="0" r="1" gradientTransform="matrix(2.91284 0 0 .57269 23.665 26.443)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="pzho1txaw"/><stop offset="1" class="r-w7u-p-k"/></radialGradient><radialGradient id="i29t2sb" cx="0" cy="0" r="1" gradientTransform="matrix(3.0548 0 0 .35964 23.558 27.832)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="pzho1txaw"/><stop offset="1" class="r-w7u-p-k"/></radialGradient><radialGradient id="i4qOaJe" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 39.685 -38.293)scale(2.79862 3.41699)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="io1Ypjc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 45.691 -49.386)scale(1.33536)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="i0YJxqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09945 0 0 -1.05169 10.492 12.54)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="ief4m0U" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.782 7.991)scale(7.33069 9.81201)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="irx1anN" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1595 1.14224 -.96911 -1.83219 17.213 12.704)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iLRMhgf" cx="0" cy="0" r="1" gradientTransform="rotate(-78.311 18.144 1.46)scale(4.22825 5.36486)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="icPUDCl" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.23941 -11.4982 0 15 11.495)" gradientUnits="userSpaceOnUse"><stop offset=".615" class="nxtspxa0z"/><stop offset=".947" class="n1_wvlq5b"/><stop offset="1" class="lhtpiip9k"/></radialGradient><radialGradient id="iwbzo5a" cx="0" cy="0" r="1" gradientTransform="matrix(-5.55048 1.5349 -2.64263 -9.55622 15.91 13.685)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="i1e8Rze" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17792 1.44563 0 17.624 11.561)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iZObare" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39208 1.59542 0 13.305 11.65)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iT9tB0c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37873 0 0 -4.53881 20.484 13.084)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="ivVFlCe" cx="0" cy="0" r="1" gradientTransform="rotate(159.839 6.677 6.958)scale(6.89096 6.0187)" gradientUnits="userSpaceOnUse"><stop class="h688fvbek"/><stop offset="1" class="u0fd5zb0p"/></radialGradient><radialGradient id="iGtB32b" cx="0" cy="0" r="1" gradientTransform="rotate(121.477 4.536 7.972)scale(.89772 2.15988)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="aj068gbhp"/><stop offset="1" class="th5h3ib6i"/></radialGradient><radialGradient id="ipVVvpF" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 13.256 .847)scale(2.60718 1.49186)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="igVlJAA" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31177 .93699 -1.25503 -1.75701 15.562 13.462)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="i6DS8Zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83046 -1.32093 0 17.502 11.929)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iSdfRTm" cx="0" cy="0" r="1" gradientTransform="matrix(-.23686 -.30523 .42023 -.3261 17.267 12.015)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iALN5Jc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83046 -1.32094 0 13.034 11.929)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iSl88ze" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.353 -.195)scale(.50537 .60747)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1ygJYZ" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 4.967 5.653)scale(5.49618 2.39705)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iLbH6rb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.17596 2.2689 -1.12133 -1.5696 12.346 5.984)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iC5KNzd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2369 4.6625 -6.61997 -3.17602 17.102 4.223)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iLcrXvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9652 3.38632 -7.09666 -2.02274 17.836 5.506)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iq4izgd" cx="0" cy="0" r="1" gradientTransform="rotate(-117.848 11.618 .68)scale(7.48709 6.69299)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><linearGradient id="iJpod9c" x1="20.072" x2="12.66" y1="5.423" y2="19.183" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="icpvgWn" x1="17.072" x2="15.675" y1="27.026" y2="26.723" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iCpsSzd" x1="7.369" x2="6.198" y1="26.825" y2="26.825" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iEYjmre" x1="23.298" x2="23.941" y1="26.911" y2="26.88" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="izYYXoc" x1="23.566" x2="21.784" y1="26.942" y2="26.942" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="icNoVrb" x1="22.941" x2="18.566" y1="16.896" y2="29.406" gradientUnits="userSpaceOnUse"><stop class="p3s97ubgt"/><stop offset="1" class="uhr48tggx"/></linearGradient><linearGradient id="iUNJ9Gd" x1="17.656" x2="18.125" y1="23.664" y2="23.75" gradientUnits="userSpaceOnUse"><stop class="n-07uqbej"/><stop offset="1" class="k5vnjbbpd"/></linearGradient><linearGradient id="ikBOvzL" x1="23.672" x2="23" y1="21.25" y2="20.969" gradientUnits="userSpaceOnUse"><stop offset=".258" class="e6ztocy0u"/><stop offset="1" class="tjnac7b5i"/></linearGradient><linearGradient id="i4OAhLd" x1="9.125" x2="12.066" y1="17.417" y2="29.786" gradientUnits="userSpaceOnUse"><stop class="yhs78-b2s"/><stop offset="1" class="ou99nli7g"/></linearGradient><linearGradient id="iVyMdve" x1="13.578" x2="13.031" y1="26.484" y2="26.594" gradientUnits="userSpaceOnUse"><stop class="tyg1xhaog"/><stop offset="1" class="wn22vh-9z"/></linearGradient><linearGradient id="ip4B8ge" x1="8.284" x2="10.566" y1="28.755" y2="27.598" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="ijnUkye" x1="10.047" x2="9.183" y1="26.774" y2="27.288" gradientUnits="userSpaceOnUse"><stop class="a9i5gdgdq"/><stop offset="1" class="qrkl270nd"/></linearGradient><linearGradient id="iurx9Ld" x1="17.925" x2="16.418" y1="23.248" y2="22.998" gradientUnits="userSpaceOnUse"><stop offset=".061" class="ko-tlzp-g"/><stop offset="1" class="hk3yvnfuu"/></linearGradient><linearGradient id="iZDSDze" x1="12.761" x2="13.728" y1="19.29" y2="19.29" gradientUnits="userSpaceOnUse"><stop class="lvtr6bbsk"/><stop offset="1" class="n-lt-i3fh"/></linearGradient><linearGradient id="i8gzboc" x1="17.654" x2="17.091" y1="19.059" y2="19.059" gradientUnits="userSpaceOnUse"><stop class="lvtr6bbsk"/><stop offset="1" class="n-lt-i3fh"/></linearGradient><linearGradient id="idbwerS" x1="25.909" x2="25.909" y1="16.592" y2="20.649" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="ijlSSJc" x1="26.104" x2="25.962" y1="17.528" y2="18.732" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="ifZKqEc" x1="23.406" x2="23.533" y1="17.465" y2="17.901" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="i8pN00b" x1="27.107" x2="24.819" y1="22.035" y2="22.035" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="iAnmTXx" x1="24.636" x2="25.017" y1="21.878" y2="21.85" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="i6YDFhE" x1="27.254" x2="26.992" y1="21.749" y2="21.725" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="icAvcDc" x1="28.191" x2="23.665" y1="27.282" y2="27.282" gradientUnits="userSpaceOnUse"><stop class="kwbcosrfm"/><stop offset=".861" class="rfqu9yc3v"/></linearGradient><linearGradient id="iK4bu1c" x1="25.801" x2="23.738" y1="25.002" y2="25.002" gradientUnits="userSpaceOnUse"><stop class="qebm4hycr"/><stop offset="1" class="b9b7yqeyc"/></linearGradient><linearGradient id="iUhOFDT" x1="25.801" x2="23.738" y1="26.443" y2="26.443" gradientUnits="userSpaceOnUse"><stop class="qebm4hycr"/><stop offset="1" class="b9b7yqeyc"/></linearGradient><linearGradient id="iB87UDg" x1="25.801" x2="23.738" y1="27.873" y2="27.873" gradientUnits="userSpaceOnUse"><stop class="qebm4hycr"/><stop offset="1" class="b9b7yqeyc"/></linearGradient><linearGradient id="iRTZr8d" x1="8.825" x2="11.854" y1="12.629" y2="12.629" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iWrfjce" x1="15.268" x2="15.268" y1="14.626" y2="11.881" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ik249zd" x1="14.197" x2="15.072" y1="13.846" y2="13.953" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="icANAvb" x1="15.268" x2="15.268" y1="14.72" y2="14.096" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iTYQo2b" x1="15.348" x2="15.348" y1="14.694" y2="14.551" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iYs8s7G" x1="14.522" x2="14.985" y1="16.232" y2="15.34" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iXLbM1d" x1="18.297" x2="17.976" y1="11.983" y2="12.181" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ici52Bb" x1="13.795" x2="13.474" y1="11.983" y2="12.181" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJ1SA4b" x1="12.309" x2="12.866" y1="6.195" y2="7.499" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><filter id="iEiXAlc" width="15.622" height="15.622" x="7.582" y="3.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="iu5Kveb" width="5.513" height="4.74" x="13.018" y="24.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="iVkNXCd" width="6.102" height="1.228" x="22.961" y="17.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="i4uclnb" width="1.075" height="1.075" x="25.369" y="21.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13949_3563" result="effect2_innerShadow_13949_3563"/></filter><filter id="iPJiENy" width="5.519" height="6.076" x="23.298" y="23.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="iWqMCDb" width="2.269" height=".25" x="23.788" y="24.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".05"/></filter><filter id="iDh3Gnb" width="2.269" height=".25" x="23.788" y="26.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".05"/></filter><filter id="iZGbCyd" width="2.269" height=".25" x="23.788" y="27.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".05"/></filter><filter id="itmb0Mb" width="3.394" height="3.294" x="8.825" y="10.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="iXQVoGc" width="3.294" height="3.544" x="18.562" y="10.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="iE19PYC" width="3.199" height="3.199" x="18.61" y="10.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".25"/></filter><filter id="iJJpEPe" width="2.699" height="2.699" x="9.142" y="11.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".125"/></filter><filter id="ibZCRYb" width="10.431" height="11.533" x="10.052" y="7.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="i7VANVj" width="2.922" height="3.745" x="13.641" y="11.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".25"/></filter><filter id="iKS8twd" width="2.422" height="3.245" x="14.057" y="11.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".125"/></filter><filter id="iVTdgWb" width="3.78" height="1.553" x="13.378" y="14.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".05"/></filter><filter id="iOWplPe" width="3.067" height="1.316" x="16.237" y="11.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="ipxnzmd" width="3.067" height="1.316" x="11.232" y="11.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="i86aMrd" width="2.506" height="1.112" x="11.37" y="9.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="i8UbPGe" width="2.506" height="1.112" x="16.915" y="9.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13949_3563"/></filter><filter id="iCOPapc" width=".799" height=".707" x="16.752" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".05"/></filter><filter id="i5osuLe" width=".902" height=".924" x="17.615" y="11.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".1"/></filter><filter id="iVa13lc" width=".999" height="1.054" x="13.067" y="11.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".1"/></filter><filter id="i5epZoe" width=".929" height=".716" x="12.292" y="11.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".05"/></filter><filter id="i3MGpac" width="2.7" height="1.387" x="16.753" y="9.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".2"/></filter><filter id="ibXgVYb" width="2.7" height="1.387" x="11.173" y="9.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".2"/></filter><filter id="iDIWaFb" width="5.068" height="5.301" x="8.42" y="5.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".375"/></filter><filter id="iusQLtd" width="9.113" height="5.905" x="11.878" y="4.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".125"/></filter><filter id="ijAzVPe" width="1.158" height="2.35" x="12.009" y="5.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13949_3563" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-singer" /></template>
<style>
.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.a9i5gdgdq {
  stop-color: var(--svg-color--55447c, #55447C);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.aj068gbhp {
  stop-color: var(--svg-color--d11458, #D11458);
}

.apsa9cl1l {
  stop-color: var(--svg-color--7955b5, #7955B5);
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.b277vn5kc {
  stop-color: var(--svg-color--fa8e2d, #FA8E2D);
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.b9b7yqeyc {
  stop-color: var(--svg-color--d58628, #D58628);
}

.bpqpsabpn {
  d: path("M14.65 4.565c-1.159-.255-2.402.978-2.522 1.407c1.579 3.706 4.003 3.353 6.692 3.054c1.61-.179 1.784.555 1.921.91c-.446-4.152-3.448-4.787-6.09-5.37");
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bvnc75b9w {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.437 11.957c.272-.477.685-.855 1.574-.855c.389 0 .764.108 1.098.378c.275.222.238.506.025.613l-.57.325c-.666-.216-1.404-.245-2.127-.46");
}

.bwu4585sd {
  cx: 12.757px;
  cy: 11.831px;
  rx: 0.398px;
  ry: 0.202px;
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.cinmdjbay {
  stop-color: var(--svg-color--ee883d, #EE883D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.d40ufvb0p {
  stop-color: var(--svg-color--ee883d, #EE883D);
  stop-opacity: 0;
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.d6y68cbbg {
  stop-color: var(--svg-color--e16a06, #E16A06);
  stop-opacity: 0;
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dempr2dnp {
  stop-color: var(--svg-color--ff4b39, #FF4B39);
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.dl98_lb6u {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.82 11.162a1.43 1.43 0 0 0-1.386 1.084a.28.28 0 0 0 .274.349h2.284a.236.236 0 0 0 .232-.278a1.434 1.434 0 0 0-1.403-1.155");
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dvc58kbnt {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.1 11.957c-.272-.477-.685-.855-1.574-.855c-.39 0-.765.108-1.098.378c-.276.222-.239.506-.026.613l.57.325c.667-.216 1.404-.245 2.127-.46");
}

.e00j6fbsx {
  stop-color: var(--svg-color--e16a06, #E16A06);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.e6ztocy0u {
  stop-color: var(--svg-color--876bc0, #876BC0);
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.enrfq8h_k {
  d: path("M7.248 29.396v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.exrdolbwt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.913 27.873h2.019");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fnokm46vs {
  stop-color: var(--svg-color--ff4b39, #FF4B39);
  stop-opacity: 0;
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gdjntuneq {
  d: path("M23.298 24.283c0-.44.366-.803.816-.803h3.055c.745 0 1.348.59 1.348 1.316v3.514c0 .605-.503 1.096-1.123 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.314.187-.59.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.72a.8.8 0 0 1-.458-.721c0-.314.187-.589.458-.72a.8.8 0 0 1-.458-.72");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gtj5jfb3o {
  cx: 12.757px;
  cy: 11.831px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.398px;
  ry: 0.202px;
}

.gwxe3pb8f {
  stop-color: var(--svg-color--ffc033, #FFC033);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.h688fvbek {
  stop-color: var(--svg-color--f92f77, #F92F77);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hbbomwb3k {
  d: path("M7.248 29.396h3.87L7.248 21.8z");
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hk3yvnfuu {
  stop-color: var(--svg-color--fbb231, #FBB231);
  stop-opacity: 0;
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hr8ud0h9b {
  d: path("M18.316 12.233a.86.86 0 0 0-.236-.473l-.265.291l.12.233z");
}

.hvtkrgbbt {
  d: path("m28.384 17.436l-4.844-.02a.57.57 0 0 0-.579.579c0 .325.254.579.58.579l4.843.02a.57.57 0 0 0 .579-.579a.585.585 0 0 0-.579-.579");
}

.i1mgxs0vi {
  stop-color: var(--svg-color--efa42b, #EFA42B);
}

.i78ylcbrm {
  d: path("M10.06 11.247h.013l-.01-.271l-.01-.314c.02-.97.587-1.347.829-1.472l.052-.02l.053-.022c.546-.25.986-.69 1.217-1.264l.084-.198a.27.27 0 0 1 .473-.052a3.95 3.95 0 0 0 3.264 1.713h3.296c.184 0 1.108.089 1.163 1.363l-.122 3.146c-.126 2.868-2.366 4.795-5.1 4.795c-2.735 0-4.975-1.927-5.101-4.795z");
}

.i7z7cdbov {
  d: path("m14.877 12.17l-.544 1.74a.552.552 0 0 0 .533.716h.805a.554.554 0 0 0 .532-.716l-.544-1.74c-.116-.385-.66-.385-.782 0");
}

.ibnsaxbhm {
  d: path("M20.21 13.64a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.is335clhe {
  fill-rule: evenodd;
  d: path("M22.623 13.983a3.3 3.3 0 0 0 .331-1.46c0-.48-.098-.928-.275-1.337h.006a3.3 3.3 0 0 0-.288-.525l-.002-.003a3.3 3.3 0 0 1-.539-1.813v-.01a3.377 3.377 0 0 0-3.377-3.377a.55.55 0 0 1-.466-.239a3.38 3.38 0 0 0-2.745-1.408c-1.13 0-2.134.559-2.745 1.408a.58.58 0 0 1-.466.239h-.087a3.38 3.38 0 0 0-3.29 3.377v.01a3.3 3.3 0 0 1-.539 1.813l-.002.004a3.38 3.38 0 0 0-.226 3.32a.53.53 0 0 1 0 .467a3.34 3.34 0 0 0-.331 1.44a3.29 3.29 0 0 0 3.294 3.294h8.784a3.29 3.29 0 0 0 3.294-3.294a3.34 3.34 0 0 0-.331-1.44a.53.53 0 0 1 0-.466m-12.55-2.736h-.012l1.227 2.412c.126 2.868 1.245 0 3.98 0s3.927 3.193 4.053.324l1.163-3.273c-.055-1.274-.979-1.363-1.163-1.363h-3.296a3.95 3.95 0 0 1-3.264-1.713a.27.27 0 0 0-.473.052l-.084.199a2.36 2.36 0 0 1-1.217 1.263q-.024.008-.053.021l-.052.021c-.242.125-.809.501-.83 1.473l.01.313z");
}

.it9idqgsx {
  stop-color: var(--svg-color--f08c3e, #F08C3E);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j1w5a6hgo {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.373 10.111c-.33-.08-1.151-.04-1.7.353");
}

.j6kqqqjso {
  d: path("M13.866 12.245c0-.294-.24-.49-.305-.55l-.294.285l.181.369z");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.ji3tmwq8i {
  stop-color: var(--svg-color--7955b5, #7955B5);
  stop-opacity: 0;
}

.jjpsrbe0r {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.21 13.64a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.jp31o1b_h {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M10.492 13.64a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.k5687y9rf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.309 5.844c.023.248.24 1.183.557 1.75");
}

.k5vnjbbpd {
  stop-color: var(--svg-color--845ebf, #845EBF);
  stop-opacity: 0;
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k7fvrbbpb {
  stop-color: var(--svg-color--ffd033, #FFD033);
}

.kadpdpbne {
  d: path("M13.033 11.44a.914.914 0 0 0-.88 1.155h1.764a1 1 0 0 0 .033-.241a.92.92 0 0 0-.917-.914");
}

.kgods_8bf {
  d: path("M25.906 22.524a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.ko-tlzp-g {
  stop-color: var(--svg-color--ce6f07, #CE6F07);
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.kwbcosrfm {
  stop-color: var(--svg-color--ffe432, #FFE432);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l1asq8nfe {
  stop-color: var(--svg-color--815eb7, #815EB7);
  stop-opacity: 0;
}

.l1fr7gb1j {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M13.018 24.656v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.l4mrzh3bf {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m14.866 12.312l-.7 1.74a.552.552 0 0 0 .533.716h.805a.554.554 0 0 0 .533-.716l-.544-1.74c-.116-.385-.505-.385-.627 0");
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhtpiip9k {
  stop-color: var(--svg-color--ee8268, #EE8268);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lqgbnzbne {
  d: path("M5.575 17.417h5.256a1 1 0 0 1 .983.816l2.095 11.173h-2.79L5.24 17.877c-.085-.125-.07-.46.336-.46");
}

.lsuuu0h2r {
  d: path("M23.298 29.396v-7.302l-3.52 7.302z");
}

.lvtr6bbsk {
  stop-color: var(--svg-color--d6802d, #D6802D);
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbkivbc6y {
  stop-color: var(--svg-color--fa8e2d, #FA8E2D);
  stop-opacity: 0;
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mi2y_fs0q {
  stop-color: var(--svg-color--6c3b70, #6C3B70);
}

.mtg46-bqu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.435 11.634c.065.087-.07.193-.225.308c-.155.116-.27.197-.334.11c-.065-.087.008-.25.162-.366s.332-.139.397-.052");
}

.n-07uqbej {
  stop-color: var(--svg-color--8e5280, #8E5280);
}

.n-lt-i3fh {
  stop-color: var(--svg-color--d6802d, #D6802D);
  stop-opacity: 0;
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n1_wvlq5b {
  stop-color: var(--svg-color--e37f55, #E37F55);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.nvzbckocx {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.716 11.162c.668 0 1.233.461 1.386 1.084a.28.28 0 0 1-.274.349h-2.283a.236.236 0 0 1-.233-.278a1.43 1.43 0 0 1 1.403-1.155");
}

.nxtspxa0z {
  stop-color: var(--svg-color--e49040, #E49040);
  stop-opacity: 0;
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o2w9f1bnl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.913 25.002h2.019");
}

.o7wsyd3ap {
  d: path("M27.447 21.72c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.omp7-5b0i {
  fill-rule: evenodd;
  d: path("M14.266 8.937a3.9 3.9 0 0 1-1.505-1.303a.27.27 0 0 0-.467.04l-1.906 5.61h1.895l-.522 2.921l3.92-5.504h-2.02z");
}

.ou99nli7g {
  stop-color: var(--svg-color--9266df, #9266DF);
}

.ouo32abns {
  d: path("M27.188 29.396c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p3s97ubgt {
  stop-color: var(--svg-color--8866b4, #8866B4);
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p4y5efbno {
  d: path("m24.483 17.41l-4.779.02a1 1 0 0 0-.978.816l-2.096 11.16h3.148l5.325-11.017a.685.685 0 0 0-.62-.98");
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pklbb-bat {
  fill: var(--svg-color--000, #000);
  d: path("M13.556 12.354a.52.52 0 0 0-.524-.523a.52.52 0 0 0-.465.764h.926a.5.5 0 0 0 .063-.241");
}

.pzho1txaw {
  stop-color: var(--svg-color--ee9829, #EE9829);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q2ut5cc4l {
  d: path("M25.896 27.236a.784.784 0 0 1-.782-.71l-.67-6.429l2.976.01l-.732 6.428a.8.8 0 0 1-.792.7");
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qebm4hycr {
  stop-color: var(--svg-color--d58628, #D58628);
  stop-opacity: 0;
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qln77wdhf {
  d: path("M10.492 13.64a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qrkl270nd {
  stop-color: var(--svg-color--55447c, #55447C);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw9ryka9f {
  d: path("M25.937 20.595a2.498 2.498 0 1 0 0-4.997a2.498 2.498 0 0 0 0 4.997");
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.qyoz56odi {
  d: path("M15.288 18.296c-1.16 0-2.297.171-3.377.491l1.097 5.869c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.r-w7u-p-k {
  stop-color: var(--svg-color--ee9829, #EE9829);
  stop-opacity: 0;
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.rfqu9yc3v {
  stop-color: var(--svg-color--f5a32b, #F5A32B);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rj47jswmc {
  d: path("M20.21 14.187a1.647 1.647 0 1 0 0-3.294a1.647 1.647 0 0 0 0 3.294");
}

.rssb04bxd {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.268 15.52a3.1 3.1 0 0 1-1.455-.353c-.144-.075-.299.091-.208.225a1.977 1.977 0 0 0 3.326 0c.09-.14-.064-.3-.208-.225a3.1 3.1 0 0 1-1.455.353");
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s5j8b3t1r {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.253 10.111c.33-.08 1.151-.04 1.7.353");
}

.sezmncb3p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.913 26.443h2.019");
}

.sf7ql_tih {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.088 10.252l-.142.235za.275.275 0 0 1-.283.47l-.004-.002a1 1 0 0 0-.116-.06a3 3 0 0 0-.35-.138a2.3 2.3 0 0 0-1.098-.094a.275.275 0 0 1-.095-.54a2.9 2.9 0 0 1 1.36.111a3.4 3.4 0 0 1 .571.244l.01.006l.003.002z");
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t0h--bk_d {
  stop-color: var(--svg-color--f0972b, #F0972B);
}

.t9zkmquqg {
  stop-color: var(--svg-color--ffc033, #FFC033);
  stop-opacity: 0;
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.th5h3ib6i {
  stop-color: var(--svg-color--d11458, #D11458);
  stop-opacity: 0;
}

.tjnac7b5i {
  stop-color: var(--svg-color--8263bd, #8263BD);
  stop-opacity: 0;
}

.tod4lrkkn {
  d: path("M10.258 6.384c.636-.566 1.553-.572 2.068-.48l.412 1.32c-.264-.04-.498.052-.695.241c-.467 1.29-2.07 2.002-2.814 2.196c-.154-1.527-.069-2.299 1.03-3.277");
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.tv3x8ynxn {
  d: path("M13.018 24.656v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.tyg1xhaog {
  stop-color: var(--svg-color--6e3c78, #6E3C78);
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u0fd5zb0p {
  stop-color: var(--svg-color--c6385e, #C6385E);
}

.u7id6gble {
  stop-color: var(--svg-color--ffe945, #FFE945);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.uhr48tggx {
  stop-color: var(--svg-color--7f54c6, #7F54C6);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.ur6jocr6m {
  d: path("M17.504 11.44a.914.914 0 0 1 .88 1.155h-1.765a.917.917 0 0 1 .884-1.154");
}

.uv8wvy1nd {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m11.79 10.72l-.004.003a.275.275 0 0 1-.282-.471l.001-.001l.003-.002l.01-.006l.033-.018q.042-.023.119-.06c.1-.048.244-.11.42-.166a2.9 2.9 0 0 1 1.36-.111a.274.274 0 0 1-.096.54c-.408-.072-.8 0-1.097.094a3 3 0 0 0-.467.198");
}

.v-reotlad {
  d: path("M10.472 14.187a1.647 1.647 0 1 0 0-3.294a1.647 1.647 0 0 0 0 3.294");
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wn22vh-9z {
  stop-color: var(--svg-color--825db9, #825DB9);
  stop-opacity: 0;
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wv0s8obst {
  fill: var(--svg-color--000, #000);
  d: path("M16.98 12.354c0-.29.233-.523.524-.523a.52.52 0 0 1 .465.764h-.926a.5.5 0 0 1-.062-.241");
}

.x2b-z-btr {
  d: path("M17.435 11.634c.065.087-.07.193-.225.308c-.155.116-.27.197-.334.11c-.065-.087.008-.25.162-.366s.332-.139.397-.052");
}

.xcnvxobld {
  stop-color: var(--svg-color--f5a511, #F5A511);
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.ydn9dmb6d {
  stop-color: var(--svg-color--ffe945, #FFE945);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yhs78-b2s {
  stop-color: var(--svg-color--7c5aad, #7C5AAD);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yow4o5baa {
  d: path("M12.982 16.262h4.572v2.8c0 1.262-1.024 1.977-2.286 1.977s-2.286-.715-2.286-1.978z");
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zsjn6kjhx {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.837 15.123c.413.22.906.347 1.431.347c.53 0 1.018-.126 1.432-.347a.21.21 0 0 1 .252.042c.059.063.08.163.021.254m-3.136-.296l3.094.269m-3.095-.269a.21.21 0 0 0-.252.044a.2.2 0 0 0-.02.252m.272-.296l-.23.269m3.367.027l-.042-.027m.042.027l-.042-.027m.042.027a2.028 2.028 0 0 1-3.41 0m3.368-.027a1.977 1.977 0 0 1-3.326 0m-.042.027l.042-.027m-.042.027l.042-.027");
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
