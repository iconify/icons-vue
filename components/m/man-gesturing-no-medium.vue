<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHNLxLc)"><circle fill="url(#iSSazFe)" class="hnxs8zbbf"/></g><circle fill="url(#iznU7Lb)" class="hnxs8zbbf"/><g filter="url(#iPFdGAe)"><circle fill="url(#iYFenRt)" class="an9q83qsj"/></g><g filter="url(#ieFnGCb)"><circle fill="url(#iffQAib)" class="y20yu1lyj"/><circle fill="url(#itwnSDc)" class="y20yu1lyj"/></g><g filter="url(#iZ5s1cZ)"><circle class="anj92bc9p"/><circle fill="url(#i1ydK9d)" class="v2k8z0b4n"/><circle fill="url(#iACviHe)" class="v2k8z0b4n"/></g><g filter="url(#irlm2nl)"><path fill="url(#ijmYwPd)" class="uoksuflot"/><path fill="url(#ih3V4vp)" class="uoksuflot"/><path fill="url(#iwUTJlb)" class="uoksuflot"/></g><path fill="url(#iZTulme)" class="loo4kwr-z"/><path fill="url(#iPjTD9b)" class="loo4kwr-z"/><path fill="url(#iZFJy3X)" class="loo4kwr-z"/><path fill="url(#iAVuYje)" class="loo4kwr-z"/><path fill="url(#iTPMO4c)" class="loo4kwr-z"/><g filter="url(#i0xx2Dy)"><path fill="url(#iPrNAnd)" class="zf6r86sju"/></g><g filter="url(#i4UtiNb)"><path class="crlxrrl1d"/><path fill="url(#iPXfyke)" class="q-kuwrbog"/><path fill="url(#izLSs1R)" class="q-kuwrbog"/><path fill="url(#iWGCe5r)" class="q-kuwrbog"/><path fill="url(#isYV9Yb)" class="q-kuwrbog"/></g><g filter="url(#iOjRrwd)"><path class="wmh_5aczf"/></g><g filter="url(#iifILwc)"><path class="hvtdkjhvr"/><path fill="url(#ieLYgoe)" class="bbdrxfbej"/><path fill="url(#iymwMzb)" class="bbdrxfbej"/><path fill="url(#i2BVZKS)" class="bbdrxfbej"/><path fill="url(#ioUNi5R)" class="bbdrxfbej"/></g><path class="d2kp3vbqs"/><path fill="url(#iSFnDEG)" class="w947kj2hz"/><path class="gakc5accb"/><g filter="url(#isZpYgc)"><path class="u_3f2jhix"/><path fill="url(#izRUJrd)" class="vob-f_bxv"/></g><g filter="url(#ifhiOjc)"><path fill="url(#i4mGq0b)" class="rkpbizb-o"/></g><path class="x6_tysffl"/><path fill="url(#ibK5l5b)" class="z55epacyi"/><path class="zjegz3byn"/><g filter="url(#iI3vyvB)"><path fill="url(#iNAoqJc)" class="s100slbon"/></g><g filter="url(#ie04zSc)"><ellipse transform="rotate(-27.914 12.745 11.924)" class="u2m3ssi1k"/><ellipse fill="url(#iVpt2Bb)" transform="rotate(-27.914 12.745 11.924)" class="q4mu_6esj"/></g><g filter="url(#i5t3y5b)"><path stroke="url(#i51v7jc)" class="w0htf_b1a"/></g><path class="yn-fx56tl"/><path fill="url(#idNXREf)" class="flhxnmbwt"/><path fill="url(#imdQJZb)" class="flhxnmbwt"/><path fill="url(#iQIVP4J)" class="flhxnmbwt"/><path fill="url(#ifmPQTd)" class="wg1wjsb7u"/><path fill="url(#ieYmULb)" class="u6hbuebtv"/><path fill="url(#iFrXXye)" class="u6hbuebtv"/><path fill="url(#iuQIPsc)" class="u6hbuebtv"/><path fill="url(#iWZoUvd)" class="u6hbuebtv"/><path fill="url(#iecHgZV)" class="u6hbuebtv"/><path fill="url(#iLa3lne)" class="u6hbuebtv"/><path fill="url(#iMi5qbe)" class="u6hbuebtv"/><path fill="url(#iq1ubmd)" class="n1p8_kbhe"/><path fill="url(#ivlKkhc)" class="llajibfnl"/><path fill="url(#i5qGzRc)" class="llajibfnl"/><path fill="url(#iMCYyWc)" class="llajibfnl"/><path fill="url(#iB54oMb)" class="llajibfnl"/><path fill="url(#iI5AzGd)" class="llajibfnl"/><path fill="url(#iReN8de)" class="btr0zwt9c"/><path fill="url(#iNt9vMe)" class="btr0zwt9c"/><path fill="url(#iqXfXdb)" class="btr0zwt9c"/><path fill="url(#i93nQXd)" class="dtbs12b0a"/><path fill="url(#ihDF0ob)" class="dtbs12b0a"/><path fill="url(#iglqCae)" class="nmers0b3v"/><path fill="url(#ikbPOld)" class="nmers0b3v"/><path fill="url(#i0ocOQb)" class="nmers0b3v"/><path fill="url(#ieLmTEc)" class="nmers0b3v"/><g filter="url(#iE93TQd)"><path fill="url(#iN2Wdxc)" class="equkd9bzv"/><path fill="url(#iX9Wkub)" class="equkd9bzv"/></g><path fill="url(#i7R1YHd)" class="equkd9bzv"/><g filter="url(#iXwV1kb)"><path clip-rule="evenodd" class="jcw05rnap"/></g><g filter="url(#iAibzHn)"><path class="j1fjdxbwt"/></g><g filter="url(#ikESIDe)"><path clip-rule="evenodd" class="z0za02k5c"/></g><g filter="url(#ivfQi7b)"><path class="ma6s8b6fs"/></g><g filter="url(#iCxLASL)"><path fill="url(#i1vHeLe)" class="p2v1e-b3z"/></g><defs><radialGradient id="iSSazFe" cx="0" cy="0" r="1" gradientTransform="matrix(2.29005 0 0 4.0076 7.571 13.25)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iznU7Lb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.892 5.175)scale(2.162)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="itwnSDc" cx="0" cy="0" r="1" gradientTransform="matrix(1.07883 -.78554 .8966 1.23134 22.65 12.904)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="i1ydK9d" cx="0" cy="0" r="1" gradientTransform="matrix(1.07172 -1.9712 1.15375 .62728 22.11 14.32)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iACviHe" cx="0" cy="0" r="1" gradientTransform="matrix(.33836 .33493 -.43177 .4362 22.165 13.249)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="ih3V4vp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.7057 2.09932 0 19.007 11.59)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iwUTJlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.79317 2.22997 0 13.06 11.765)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iZFJy3X" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.6716 -14.4861 0 15.558 10.95)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="kwao9fbqu"/><stop offset="1" class="wv6j595ib"/></radialGradient><radialGradient id="iTPMO4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.79651 9.63995 0 14.007 19.778)" gradientUnits="userSpaceOnUse"><stop class="ii8pycbjh"/><stop offset="1" class="u3hpzdbjz"/></radialGradient><radialGradient id="iPXfyke" cx="0" cy="0" r="1" gradientTransform="matrix(1.04113 -3.8583 1.43077 .38608 21.616 7.89)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="izLSs1R" cx="0" cy="0" r="1" gradientTransform="matrix(4.9913 .45932 -.24697 2.68379 19.473 5.594)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iWGCe5r" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.19127 -3.39366 0 15.946 2.025)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="isYV9Yb" cx="0" cy="0" r="1" gradientTransform="matrix(4.0114 -2.93967 4.6055 6.28455 7.53 10.922)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="ioUNi5R" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25695 -.82552 0 16.373 14.734)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iSFnDEG" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0585 -1.68367 0 18.793 12.05)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="izRUJrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30258 -.38991 .53681 -.41657 18.495 12.159)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibK5l5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05856 -1.68375 0 13.1 12.05)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVpt2Bb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.435 -.096)scale(.6447 .77494)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idNXREf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.8125 10.4384 0 16.562 30.378)" gradientUnits="userSpaceOnUse"><stop class="mebiusz6j"/><stop offset=".714" class="tzc2eqbez"/></radialGradient><radialGradient id="imdQJZb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.413)" gradientUnits="userSpaceOnUse"><stop class="tkk3fh7lv"/><stop offset="1" class="wltqj-b_b"/></radialGradient><radialGradient id="iQIVP4J" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.194)" gradientUnits="userSpaceOnUse"><stop class="stmwvtbwq"/><stop offset="1" class="mbu8hk88e"/></radialGradient><radialGradient id="ifmPQTd" cx="0" cy="0" r="1" gradientTransform="matrix(2.6551 1.32154 -2.0509 4.12044 8.345 17.216)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="lht-5qo7r"/><stop offset="1" class="c83rl0b_v"/></radialGradient><radialGradient id="ieYmULb" cx="0" cy="0" r="1" gradientTransform="matrix(16.5217 8.52358 -2.95327 5.72447 14.913 18.632)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="a7qi3ibbq"/><stop offset="1" class="isu90b6vd"/></radialGradient><radialGradient id="iFrXXye" cx="0" cy="0" r="1" gradientTransform="matrix(-4.80476 2.04336 -1.52855 -3.59423 29 24.879)" gradientUnits="userSpaceOnUse"><stop class="bpjtw3boo"/><stop offset="1" class="g_enp1bol"/></radialGradient><radialGradient id="iuQIPsc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07575 5.3158 -8.32749 -3.25178 14.245 17.66)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="avgknr4aj"/><stop offset="1" class="xp9lv-a7q"/></radialGradient><radialGradient id="iecHgZV" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.4 -3.087)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="pe78akl1z"/><stop offset="1" class="epnh4ac5k"/></radialGradient><radialGradient id="iMi5qbe" cx="0" cy="0" r="1" gradientTransform="matrix(8.43038 -3.42291 .46766 1.15182 16.663 24.88)" gradientUnits="userSpaceOnUse"><stop offset=".314" class="mzcr1bvpw"/><stop offset="1" class="ms91oy-xv"/></radialGradient><radialGradient id="iq1ubmd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 .59375 -1.31526 -3.21892 23.405 17.785)" gradientUnits="userSpaceOnUse"><stop class="h3jyzg19k"/><stop offset="1" class="fo5-hs3pv"/></radialGradient><radialGradient id="ivlKkhc" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.85)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="a6fx42bik"/><stop offset="1" class="lrp5mrmlg"/></radialGradient><radialGradient id="iReN8de" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.436)" gradientUnits="userSpaceOnUse"><stop class="gi9rlrtiz"/><stop offset=".615" class="v4bxf0bxm"/></radialGradient><radialGradient id="i93nQXd" cx="0" cy="0" r="1" gradientTransform="rotate(25.705 -37.009 15.771)scale(1.9602 2.66792)" gradientUnits="userSpaceOnUse"><stop class="o6yqkabjh"/><stop offset=".697" class="iuvvk27wi"/></radialGradient><radialGradient id="ihDF0ob" cx="0" cy="0" r="1" gradientTransform="matrix(-.8664 .26697 -.4987 -1.61843 4.818 17.175)" gradientUnits="userSpaceOnUse"><stop class="e-dsjlbgb"/><stop offset="1" class="e4hi5lpxu"/></radialGradient><radialGradient id="iglqCae" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.291 6.34)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="il1-__z0c"/><stop offset="1" class="bw58smb4a"/></radialGradient><radialGradient id="ikbPOld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 .59376 -.2045 -.35517 30.16 13.194)" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="egju40ogk"/></radialGradient><radialGradient id="ieLmTEc" cx="0" cy="0" r="1" gradientTransform="rotate(-25.641 56.248 -44.008)scale(2.59977 2.78402)" gradientUnits="userSpaceOnUse"><stop class="c64g55i6x"/><stop offset="1" class="ej8zfjbhh"/></radialGradient><radialGradient id="iX9Wkub" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.255)" gradientUnits="userSpaceOnUse"><stop class="jdjo_xq8q"/><stop offset="1" class="s3mfozy-p"/></radialGradient><radialGradient id="i7R1YHd" cx="0" cy="0" r="1" gradientTransform="matrix(1.00475 -.26214 .85754 3.28688 4.382 18.16)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="mhzmsi1xs"/><stop offset="1" class="wbpqeub1g"/></radialGradient><linearGradient id="iYFenRt" x1="9.75" x2="8.914" y1="13.613" y2="13.613" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iffQAib" x1="23.582" x2="22.514" y1="11.825" y2="15.134" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="ijmYwPd" x1="21.213" x2="11.247" y1="13.757" y2="15.242" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iZTulme" x1="8.904" x2="11.36" y1="17.276" y2="17.188" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iPjTD9b" x1="22.367" x2="20.916" y1="16.177" y2="16.051" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iAVuYje" x1="15.983" x2="15.983" y1="20.404" y2="21.773" gradientUnits="userSpaceOnUse"><stop offset=".533" class="n3-c-obfq"/><stop offset="1" class="o40bvx3go"/></linearGradient><linearGradient id="iPrNAnd" x1="15.252" x2="25.88" y1="9.862" y2="6.057" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="ieLYgoe" x1="14.818" x2="16.042" y1="14.006" y2="14.006" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iymwMzb" x1="17.17" x2="15.832" y1="14.427" y2="14.408" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="i2BVZKS" x1="16.174" x2="16.261" y1="15.634" y2="13.155" gradientUnits="userSpaceOnUse"><stop class="p_iww9tjh"/><stop offset=".697" class="wh1buh49v"/></linearGradient><linearGradient id="i4mGq0b" x1="19.808" x2="19.398" y1="12.12" y2="12.372" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iNAoqJc" x1="14.07" x2="13.66" y1="12.12" y2="12.372" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i51v7jc" x1="9.862" x2="9.862" y1="6.842" y2="9.656" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="iWZoUvd" x1="9.156" x2="10.486" y1="18.475" y2="19.099" gradientUnits="userSpaceOnUse"><stop class="y6shzzc0m"/><stop offset="1" class="gvfnv53tr"/></linearGradient><linearGradient id="iLa3lne" x1="17.482" x2="17.906" y1="26.681" y2="25.725" gradientUnits="userSpaceOnUse"><stop class="oo6zkeb_e"/><stop offset=".46" class="bw5w8zblw"/></linearGradient><linearGradient id="i5qGzRc" x1="15.132" x2="14.231" y1="27.536" y2="25.512" gradientUnits="userSpaceOnUse"><stop offset=".205" class="boish7bqf"/><stop offset="1" class="dalry_j2d"/></linearGradient><linearGradient id="iMCYyWc" x1="10.345" x2="11.438" y1="19.427" y2="21.958" gradientUnits="userSpaceOnUse"><stop class="m8jyzebhe"/><stop offset="1" class="h7od31b_t"/></linearGradient><linearGradient id="iB54oMb" x1="22.827" x2="21.613" y1="18.787" y2="19.35" gradientUnits="userSpaceOnUse"><stop class="r_-h96bdp"/><stop offset="1" class="tvrmq9s8w"/></linearGradient><linearGradient id="iI5AzGd" x1="3.231" x2="6.517" y1="28.262" y2="26.655" gradientUnits="userSpaceOnUse"><stop class="vxp4qyb9c"/><stop offset="1" class="amr862j1l"/></linearGradient><linearGradient id="iNt9vMe" x1="27.52" x2="26.84" y1="19.632" y2="18.069" gradientUnits="userSpaceOnUse"><stop class="u8owb3akc"/><stop offset="1" class="yutka0byn"/></linearGradient><linearGradient id="iqXfXdb" x1="26.75" x2="27.494" y1="17.366" y2="18.125" gradientUnits="userSpaceOnUse"><stop offset=".353" class="r80e5wbfg"/><stop offset="1" class="n7xbqubtn"/></linearGradient><linearGradient id="i0ocOQb" x1="25.489" x2="25.997" y1="14.257" y2="15.157" gradientUnits="userSpaceOnUse"><stop class="beeyfebmi"/><stop offset="1" class="uhgt8fd7p"/></linearGradient><linearGradient id="iN2Wdxc" x1="8" x2="5.5" y1="15.725" y2="19.491" gradientUnits="userSpaceOnUse"><stop offset=".206" class="g9lwhpb_s"/><stop offset="1" class="f96e_t8ap"/></linearGradient><linearGradient id="i1vHeLe" x1="29.179" x2="24.036" y1="14.821" y2="17.689" gradientUnits="userSpaceOnUse"><stop class="ffwswni4j"/><stop offset="1" class="zcueg9l3v"/></linearGradient><filter id="iHNLxLc" width="4.557" height="4.357" x="7.571" y="11.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24802"/></filter><filter id="iPFdGAe" width="3.597" height="3.597" x="7.952" y="11.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".25"/></filter><filter id="ieFnGCb" width="4.607" height="4.607" x="19.986" y="10.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24802"/></filter><filter id="iZ5s1cZ" width="3.597" height="3.597" x="20.366" y="11.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".25"/></filter><filter id="irlm2nl" width="13.537" height="15.946" x="9.215" y="5.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24802"/></filter><filter id="i0xx2Dy" width="9.541" height="8.002" x="14.168" y="3.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation="1"/></filter><filter id="i4UtiNb" width="16.445" height="10.997" x="7.724" y="1.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24802"/></filter><filter id="iOjRrwd" width="3.797" height="4.999" x="13.736" y="11.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".375"/></filter><filter id="iifILwc" width="2.949" height="3.999" x="14.471" y="11.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".125"/></filter><filter id="isZpYgc" width=".966" height=".848" x="17.865" y="11.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".05"/></filter><filter id="ifhiOjc" width="1.041" height="1.07" x="18.992" y="11.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".1"/></filter><filter id="iI3vyvB" width="1.165" height="1.235" x="13.195" y="11.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".1"/></filter><filter id="ie04zSc" width="1.13" height=".858" x="12.18" y="11.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".05"/></filter><filter id="i5t3y5b" width="1.087" height="2.733" x="9.319" y="6.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".125"/></filter><filter id="iE93TQd" width="7.3" height="8.016" x="2" y="12.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.356863 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24802"/></filter><filter id="iXwV1kb" width="3.594" height="2.063" x="11.046" y="8.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0862745 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24802"/></filter><filter id="iAibzHn" width="3.094" height="1.313" x="11.296" y="9.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".125"/></filter><filter id="ikESIDe" width="3.594" height="2.063" x="17.523" y="8.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0862745 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24802"/></filter><filter id="ivfQi7b" width="3.094" height="1.313" x="17.773" y="9.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".125"/></filter><filter id="iCxLASL" width="5.605" height="5.453" x="24.159" y="13.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24802" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-gesturing-no-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a6fx42bik {
  stop-color: var(--svg-color--1fa4f0, #1FA4F0);
}

.a7qi3ibbq {
  stop-color: var(--svg-color--32a6f9, #32A6F9);
}

.amr862j1l {
  stop-color: var(--svg-color--3869b0, #3869B0);
  stop-opacity: 0;
}

.an9q83qsj {
  cx: 9.75px;
  cy: 13.249px;
  r: 1.298px;
}

.anj92bc9p {
  cx: 22.165px;
  cy: 13.249px;
  r: 1.298px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.avgknr4aj {
  stop-color: var(--svg-color--28bbff, #28BBFF);
}

.bbdrxfbej {
  d: path("m15.447 12.265l-.693 2.218a.704.704 0 0 0 .679.913h1.026c.48 0 .82-.464.679-.913l-.693-2.218c-.149-.491-.842-.491-.998 0");
}

.beeyfebmi {
  stop-color: var(--svg-color--8e6d54, #8E6D54);
}

.boish7bqf {
  stop-color: var(--svg-color--0d7edf, #0D7EDF);
}

.bpjtw3boo {
  stop-color: var(--svg-color--47bbff, #47BBFF);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.btr0zwt9c {
  d: path("M24.75 19.779a.885.885 0 0 1 .35-1.204l2.609-1.427a.899.899 0 1 1 .856 1.58l-2.622 1.404a.885.885 0 0 1-1.193-.353");
}

.bw58smb4a {
  stop-color: var(--svg-color--a17a65, #A17A65);
}

.bw5w8zblw {
  stop-color: var(--svg-color--4466c2, #4466C2);
  stop-opacity: 0;
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c64g55i6x {
  stop-color: var(--svg-color--a9656c, #A9656C);
}

.c83rl0b_v {
  stop-color: var(--svg-color--1f5491, #1F5491);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crlxrrl1d {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m22.234 4.796l.56.278c.98.487 1.54 1.6 1.33 2.784l-.77 3.967c-.068.41-.34.686-.746.696h-.024s.07-1.183.14-1.879c.057-.565-.041-.738-.56-1.253c-.28-.278-.49-.696-.49-1.113V7.162c0-.348-.28-.626-.56-.696c-.84-.209-2.59-.557-5.11-.557s-4.27.348-5.11.557c-.35.07-.56.348-.56.696v1.114c0 .417-.14.835-.49 1.113l-.21.21c-.28.208-.42.625-.42.973c.07.766.14 1.88.14 1.88l-.063-.002a.83.83 0 0 1-.776-.694l-.77-3.967c-.14-1.114.42-2.228 1.4-2.715l.56-.278c.35-.21.7-.487 1.05-.766l1.26-1.322c.77-.696 1.89-.905 2.87-.418c.7.209 1.47.209 2.17 0c1.05-.348 2.24-.07 3.08.696l1.05 1.044c.28.348.63.557 1.05.766");
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d2kp3vbqs {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.065 11.072c.852 0 1.572.588 1.768 1.382a.358.358 0 0 1-.35.444h-2.91a.3.3 0 0 1-.297-.354c.165-.837.9-1.472 1.79-1.472");
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dalry_j2d {
  stop-color: var(--svg-color--0d7edf, #0D7EDF);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dtbs12b0a {
  d: path("M7.246 19.748a.885.885 0 0 0-.351-1.203l-2.553-1.397a.899.899 0 1 0-.855 1.58l2.565 1.374a.885.885 0 0 0 1.194-.354");
}

.e-dsjlbgb {
  stop-color: var(--svg-color--6b4237, #6B4237);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4hi5lpxu {
  stop-color: var(--svg-color--6b4237, #6B4237);
  stop-opacity: 0;
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.egju40ogk {
  stop-color: var(--svg-color--cca68c, #CCA68C);
  stop-opacity: 0;
}

.ej8zfjbhh {
  stop-color: var(--svg-color--a9656c, #A9656C);
  stop-opacity: 0;
}

.epnh4ac5k {
  stop-color: var(--svg-color--527faa, #527FAA);
  stop-opacity: 0;
}

.equkd9bzv {
  d: path("m9 16.045l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f96e_t8ap {
  stop-color: var(--svg-color--8f575b, #8F575B);
}

.ffwswni4j {
  stop-color: var(--svg-color--c29a88, #C29A88);
}

.flhxnmbwt {
  d: path("M25.5 29.975h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.fo5-hs3pv {
  stop-color: var(--svg-color--1474c2, #1474C2);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g_enp1bol {
  stop-color: var(--svg-color--309ff1, #309FF1);
  stop-opacity: 0;
}

.g9lwhpb_s {
  stop-color: var(--svg-color--bb9373, #BB9373);
}

.gakc5accb {
  fill: var(--svg-color--000, #000);
  d: path("M18.129 12.591c0-.37.296-.667.666-.667a.664.664 0 0 1 .593.974h-1.18a.6.6 0 0 1-.08-.307");
}

.gi9rlrtiz {
  stop-color: var(--svg-color--cca58e, #CCA58E);
}

.gvfnv53tr {
  stop-color: var(--svg-color--047fc0, #047FC0);
  stop-opacity: 0;
}

.h3jyzg19k {
  stop-color: var(--svg-color--288dcd, #288DCD);
}

.h7od31b_t {
  stop-color: var(--svg-color--1481b9, #1481B9);
  stop-opacity: 0;
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hnxs8zbbf {
  cx: 9.75px;
  cy: 13.249px;
  r: 2.179px;
}

.hvtdkjhvr {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.447 12.265l-.693 2.218a.704.704 0 0 0 .679.913h1.026c.48 0 .82-.464.679-.913l-.693-2.218c-.149-.491-.842-.491-.998 0");
}

.ii8pycbjh {
  stop-color: var(--svg-color--7a6758, #7A6758);
}

.il1-__z0c {
  stop-color: var(--svg-color--a37f67, #A37F67);
}

.isu90b6vd {
  stop-color: var(--svg-color--1b73d2, #1B73D2);
}

.iuvvk27wi {
  stop-color: var(--svg-color--874f5d, #874F5D);
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j1fjdxbwt {
  stroke: var(--svg-color--473d3d, #473D3D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m11.671 9.996l2.344-.563");
}

.jcw05rnap {
  fill: var(--svg-color--352725, #352725);
  fill-rule: evenodd;
  d: path("M14.623 9.451a.625.625 0 0 1-.462.754l-2.344.563a.625.625 0 1 1-.292-1.216l2.344-.562a.625.625 0 0 1 .754.461");
}

.jdjo_xq8q {
  stop-color: var(--svg-color--c49a85, #C49A85);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kwao9fbqu {
  stop-color: var(--svg-color--975681, #975681);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lht-5qo7r {
  stop-color: var(--svg-color--3592c8, #3592C8);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llajibfnl {
  d: path("M20.44 16.074L5.033 23.246a3.53 3.53 0 0 0-1.7 4.691a3.516 3.516 0 0 0 4.679 1.705l15.407-7.183c.503-.232.724-.837.483-1.341l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.loo4kwr-z {
  d: path("M9.215 10.572c0-.348.14-.765.42-.974l.21-.209c.35-.278.49-.696.49-1.113V7.162c0-.348.21-.626.56-.696c.84-.209 2.59-.557 5.11-.557s4.27.348 5.11.557c.28.07.56.348.56.696v1.114c0 .417.21.835.49 1.113c.655.46.614.712.56 1.253c-.07.696-.14 1.88-.14 1.88l.023-.001l-.347 5.166c-.21 2.309-2.025 3.918-4.19 3.918h-4.189c-2.234 0-3.98-1.61-4.19-3.918c-.181-2.37-.26-4.748-.477-7.115");
}

.lrp5mrmlg {
  stop-color: var(--svg-color--1892ed, #1892ED);
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m8jyzebhe {
  stop-color: var(--svg-color--1481b9, #1481B9);
}

.ma6s8b6fs {
  stroke: var(--svg-color--473d3d, #473D3D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m20.491 9.996l-2.343-.563");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbu8hk88e {
  stop-color: var(--svg-color--3b7ea8, #3B7EA8);
  stop-opacity: 0;
}

.mebiusz6j {
  stop-color: var(--svg-color--1f70c6, #1F70C6);
}

.mhzmsi1xs {
  stop-color: var(--svg-color--996f67, #996F67);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.ms91oy-xv {
  stop-color: var(--svg-color--1a62c7, #1A62C7);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.mzcr1bvpw {
  stop-color: var(--svg-color--1a62c7, #1A62C7);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n1p8_kbhe {
  d: path("m25.19 20.545l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.n3-c-obfq {
  stop-color: var(--svg-color--a66d9f, #A66D9F);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n7xbqubtn {
  stop-color: var(--svg-color--8c644c, #8C644C);
  stop-opacity: 0;
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nmers0b3v {
  d: path("m23 16.045l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o40bvx3go {
  stop-color: var(--svg-color--a66d9f, #A66D9F);
}

.o6yqkabjh {
  stop-color: var(--svg-color--9b7667, #9B7667);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.oo6zkeb_e {
  stop-color: var(--svg-color--4466c2, #4466C2);
}

.p_iww9tjh {
  stop-color: var(--svg-color--6b5a58, #6B5A58);
}

.p2v1e-b3z {
  d: path("M26.653 15.598c.552-.886 1.914-1.74 2.55-2.03l.161.193c-2.198 1.332-1.99 1.837-2.775 3.177c-.355.604-1.177 1.112-1.557 1.283l-.473-.898c.53-.281 1.462-.712 2.094-1.725");
}

.pe78akl1z {
  stop-color: var(--svg-color--527faa, #527FAA);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q-kuwrbog {
  d: path("m22.234 4.796l.56.278c.98.487 1.54 1.6 1.33 2.784l-.77 3.967c-.068.41-.34.686-.746.696h-.024s.07-1.183.14-1.879c.057-.565-.041-.738-.56-1.253c-.28-.278-.49-.696-.49-1.113V7.162c0-.348-.28-.626-.56-.696c-.84-.209-2.59-.557-5.11-.557s-4.27.348-5.11.557c-.35.07-.56.348-.56.696v1.114c0 .417-.14.835-.49 1.113l-.21.21c-.28.208-.42.625-.42.973c.07.766.14 1.88.14 1.88l-.063-.002a.83.83 0 0 1-.776-.694l-.77-3.967c-.14-1.114.42-2.228 1.4-2.715l.56-.278c.35-.21.7-.487 1.05-.766l1.26-1.322c.77-.696 1.89-.905 2.87-.418c.7.209 1.47.209 2.17 0c1.05-.348 2.24-.07 3.08.696l1.05 1.044c.28.348.63.557 1.05.766");
}

.q4mu_6esj {
  cx: 12.745px;
  cy: 11.924px;
  rx: 0.508px;
  ry: 0.257px;
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r_-h96bdp {
  stop-color: var(--svg-color--46c3ff, #46C3FF);
}

.r80e5wbfg {
  stop-color: var(--svg-color--8c644c, #8C644C);
}

.rkpbizb-o {
  d: path("M19.833 12.438a1.1 1.1 0 0 0-.302-.604l-.34.372l.154.298z");
}

.s100slbon {
  d: path("M14.16 12.455c0-.377-.306-.628-.389-.703l-.376.363l.232.472z");
}

.s3mfozy-p {
  stop-color: var(--svg-color--c49a85, #C49A85);
  stop-opacity: 0;
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.stmwvtbwq {
  stop-color: var(--svg-color--3b7ea8, #3B7EA8);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.tkk3fh7lv {
  stop-color: var(--svg-color--3fc3ff, #3FC3FF);
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tvrmq9s8w {
  stop-color: var(--svg-color--46c3ff, #46C3FF);
  stop-opacity: 0;
}

.tzc2eqbez {
  stop-color: var(--svg-color--075ab5, #075AB5);
}

.u_3f2jhix {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.71 11.673c.083.111-.09.246-.288.394c-.197.147-.343.25-.426.14c-.083-.111.01-.32.207-.468c.197-.147.424-.177.507-.066");
}

.u2m3ssi1k {
  cx: 12.745px;
  cy: 11.924px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.508px;
  ry: 0.257px;
}

.u3hpzdbjz {
  stop-color: var(--svg-color--7a6758, #7A6758);
  stop-opacity: 0;
}

.u6hbuebtv {
  d: path("m11.56 16.074l15.407 7.177a3.53 3.53 0 0 1 1.7 4.688a3.52 3.52 0 0 1-4.679 1.703L8.581 22.455a1 1 0 0 1-.483-1.34l2.123-4.567a1.004 1.004 0 0 1 1.339-.474");
}

.u8owb3akc {
  stop-color: var(--svg-color--a86e75, #A86E75);
}

.uhgt8fd7p {
  stop-color: var(--svg-color--8e6d54, #8E6D54);
  stop-opacity: 0;
}

.uoksuflot {
  d: path("m9.29 12.45l.065.002s-.07-1.114-.14-1.88c0-.348.14-.765.42-.974l.21-.209c.35-.278.49-.696.49-1.113V7.162c0-.348.21-.626.56-.696c.84-.209 2.59-.557 5.11-.557s4.27.348 5.11.557c.28.07.56.348.56.696v1.114c0 .417.21.835.49 1.113c.655.46.614.712.56 1.253c-.07.696-.14 1.88-.14 1.88l.023-.001l-.347 5.166c-.21 2.309-2.025 3.918-4.19 3.918h-4.189c-2.234 0-3.98-1.61-4.19-3.918z");
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v2k8z0b4n {
  cx: 22.165px;
  cy: 13.249px;
  r: 1.298px;
}

.v4bxf0bxm {
  stop-color: var(--svg-color--b89377, #B89377);
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vob-f_bxv {
  d: path("M18.71 11.673c.083.111-.09.246-.288.394c-.197.147-.343.25-.426.14c-.083-.111.01-.32.207-.468c.197-.147.424-.177.507-.066");
}

.vxp4qyb9c {
  stop-color: var(--svg-color--3869b0, #3869B0);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w0htf_b1a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.03 6.97v1.172c-.01.194-.091.627-.336.811");
}

.w947kj2hz {
  d: path("M18.795 11.427a1.164 1.164 0 0 1 1.122 1.471h-2.249a1.2 1.2 0 0 1-.042-.307c0-.64.524-1.164 1.17-1.164");
}

.wbpqeub1g {
  stop-color: var(--svg-color--996f67, #996F67);
  stop-opacity: 0;
}

.wg1wjsb7u {
  d: path("m6.81 20.545l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.wh1buh49v {
  stop-color: var(--svg-color--a8846e, #A8846E);
  stop-opacity: 0;
}

.wltqj-b_b {
  stop-color: var(--svg-color--3fc3ff, #3FC3FF);
  stop-opacity: 0;
}

.wmh_5aczf {
  fill: var(--svg-color--6f5b54, #6F5B54);
  d: path("m15.587 12.478l-1.071 2.218c-.133.456.186.912.637.912h.962c.451 0 .77-.463.637-.912l-.65-2.218c-.14-.491-.37-.491-.516 0");
}

.wv6j595ib {
  stop-color: var(--svg-color--975681, #975681);
}

.x6_tysffl {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.826 11.072c-.852 0-1.572.588-1.767 1.382a.358.358 0 0 0 .349.444h2.911a.3.3 0 0 0 .296-.354a1.83 1.83 0 0 0-1.789-1.472");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xp9lv-a7q {
  stop-color: var(--svg-color--28bbff, #28BBFF);
  stop-opacity: 0;
}

.y20yu1lyj {
  cx: 22.165px;
  cy: 13.249px;
  r: 2.179px;
}

.y6shzzc0m {
  stop-color: var(--svg-color--047fc0, #047FC0);
}

.yn-fx56tl {
  fill: var(--svg-color--86004e, #86004E);
  d: path("M15.989 19.426c.791 0 1.433-.689 1.433-1.538s-.642-1.538-1.433-1.538s-1.433.689-1.433 1.538s.642 1.538 1.433 1.538");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.yutka0byn {
  stop-color: var(--svg-color--a86e75, #A86E75);
  stop-opacity: 0;
}

.z0za02k5c {
  fill: var(--svg-color--352725, #352725);
  fill-rule: evenodd;
  d: path("M17.54 9.451a.625.625 0 0 0 .462.754l2.344.563a.625.625 0 1 0 .291-1.216l-2.344-.562a.625.625 0 0 0-.753.461");
}

.z55epacyi {
  d: path("M13.096 11.427a1.164 1.164 0 0 0-1.122 1.471h2.25q.04-.148.042-.307a1.17 1.17 0 0 0-1.17-1.164");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zcueg9l3v {
  stop-color: var(--svg-color--c29a88, #C29A88);
  stop-opacity: 0;
}

.zf6r86sju {
  d: path("m21.118 5.91l-4.016 1.338a1.366 1.366 0 0 0 .614 2.651l3.993-.535z");
}

.zjegz3byn {
  fill: var(--svg-color--000, #000);
  d: path("M13.763 12.591a.664.664 0 0 0-.666-.667a.664.664 0 0 0-.593.974h1.18a.66.66 0 0 0 .08-.307");
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
