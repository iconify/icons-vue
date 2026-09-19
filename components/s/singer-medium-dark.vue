<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipgmxRW)"><path class="dqa4_dciz"/><path fill="url(#ijs6MRb)" class="qd55obbpm"/></g><path fill="url(#iusfDlx)" class="c5q7122zr"/><path fill="url(#iVWeYuc)" class="c5q7122zr"/><path fill="url(#i1mlueb)" class="laenz-bql"/><path fill="url(#i3Sh0Me)" class="laenz-bql"/><path fill="url(#iRwJRdd)" class="wieq7abdc"/><path fill="url(#idWSGXe)" class="wieq7abdc"/><path fill="url(#i3rHTFb)" class="wieq7abdc"/><path fill="url(#iHEj4Hy)" class="wieq7abdc"/><path fill="url(#igVhnne)" class="yebmocc2p"/><path fill="url(#ioGO8Wc)" class="yebmocc2p"/><path fill="url(#iJmVmgb)" class="yebmocc2p"/><path fill="url(#iutyKpc)" class="yebmocc2p"/><path fill="url(#idKug7c)" class="yebmocc2p"/><path fill="url(#imWK0ae)" class="u5h71mb8p"/><path fill="url(#iFkg6vb)" class="ifmu2bbjb"/><path fill="url(#izb8H2b)" class="zc7yzq-8f"/><path fill="url(#iWoVHje)" class="nzlkhptrb"/><path fill="url(#iQQWRhb)" class="nzlkhptrb"/><path fill="url(#iebJ0me)" class="nzlkhptrb"/><path fill="url(#ivHRSud)" class="ubrvwpbys"/><path fill="url(#io1vnmc)" class="ubrvwpbys"/><path fill="url(#iTohMAc)" class="bn25ibyvi"/><path fill="url(#ib4I5td)" class="bn25ibyvi"/><path fill="url(#iyulusd)" class="bn25ibyvi"/><path fill="url(#iqJGQcd)" class="bn25ibyvi"/><g filter="url(#ibjRhHc)"><path fill="url(#it2HJAe)" class="yq0mqbb7s"/><path fill="url(#isMJFCe)" class="yq0mqbb7s"/><path fill="url(#iZFWRYc)" class="yq0mqbb7s"/></g><path fill="url(#ib01T2c)" class="tpc0--b3t"/><path fill="url(#iL5Bq5b)" class="tpc0--b3t"/><path fill="url(#iUPx9Mc)" class="tpc0--b3t"/><g filter="url(#isiTqtd)"><path fill="url(#iRXIwZz)" class="ld_9npbcv"/></g><g filter="url(#iPoZECe)"><circle fill="url(#i8r9Jtd)" class="jsbpszb3m"/></g><g filter="url(#iXccOvd)"><circle fill="url(#iAyWKGb)" class="ptdv5_kap"/></g><g filter="url(#id2hEYd)"><path fill="url(#iI5Ogcb)" class="o8fqlybaq"/><path fill="url(#i69ktZc)" class="o8fqlybaq"/><path fill="url(#i6OXeEd)" class="o8fqlybaq"/><path fill="url(#ifXEcKc)" class="o8fqlybaq"/><path fill="url(#iVbCzEF)" class="o8fqlybaq"/></g><g filter="url(#iKDkfRb)"><path stroke="url(#ifMxTBb)" class="gnpanyxaf"/></g><g filter="url(#irrPhOb)"><path stroke="url(#icxHqid)" class="afbr7bclm"/></g><g filter="url(#irOvujb)"><path stroke="url(#ijTeYne)" class="pl4qbm_2r"/></g><path fill="url(#iew8KeJ)" class="k50-3zbvz"/><path fill="url(#iswBWEm)" class="zv7vnvb8h"/><g filter="url(#ijibAzd)"><path fill="url(#iaIR55d)" class="uyyuv9bgc"/><path fill="url(#ixcOA0d)" class="uyyuv9bgc"/></g><path fill="url(#i0Q8Vce)" class="uyyuv9bgc"/><path fill="url(#i5zVq2b)" class="uyyuv9bgc"/><path fill="url(#i0wAg5d)" class="uyyuv9bgc"/><path fill="url(#i28VVOb)" class="uyyuv9bgc"/><path fill="url(#iCj5lMc)" class="uyyuv9bgc"/><path fill="url(#iywZB8c)" class="uyyuv9bgc"/><path fill="url(#il3Zytc)" class="uyyuv9bgc"/><g filter="url(#iLfqbYV)"><path class="rz92qe40v"/></g><g filter="url(#i1clwgd)"><path class="xfsm94b7g"/><path fill="url(#i8dwqGc)" class="f4o-s7bti"/><path fill="url(#idTCjJd)" class="f4o-s7bti"/><path fill="url(#ifgrCAc)" class="f4o-s7bti"/><path fill="url(#iAQYIzd)" class="f4o-s7bti"/><path fill="url(#imDzmIb)" class="f4o-s7bti"/></g><path fill="url(#iaIGhun)" class="f4o-s7bti"/><path fill="url(#iNPZ2ob)" class="f4o-s7bti"/><path fill="url(#is0Ut1b)" class="cej-hnb2p"/><path fill="url(#iCEtP8b)" class="cej-hnb2p"/><g filter="url(#iJmoVye)"><path stroke="url(#iKRfGfb)" class="ika489brf"/></g><path fill="url(#i3y5zjb)" class="yk2-i9bly"/><g filter="url(#iA3qX8c)"><path fill="url(#itDcsEd)" class="dn78wjc6c"/><path fill="url(#iLGRmve)" class="dn78wjc6c"/><path fill="url(#i1Lzjbc)" class="dn78wjc6c"/><path fill="url(#iexQoMk)" class="dn78wjc6c"/><path fill="url(#ilpNdQb)" class="dn78wjc6c"/></g><g filter="url(#ib3C9Hd)"><path class="o_mg7ubnd"/></g><g filter="url(#iQyyiwb)"><path class="b3i2nrbzr"/></g><g filter="url(#iGii1ge)"><path class="zpamgqilq"/><path fill="url(#iqB5G8d)" class="g8jw3blad"/><path fill="url(#irbm1eb)" class="g8jw3blad"/></g><g filter="url(#iopNlXd)"><path class="dq1_3f5_w"/><path fill="url(#iOXcBqM)" class="tfcaisbid"/><path fill="url(#iz0gsKd)" class="tfcaisbid"/></g><path class="s0w4_5u6c"/><path fill="url(#iQMfn3c)" class="gxelnbrlp"/><path class="fd9sf-bzr"/><g filter="url(#i8blhgc)"><path class="qu5sukbjz"/><path fill="url(#iBaYotd)" class="r35zuwb1w"/></g><g filter="url(#iPIleNe)"><path fill="url(#iatORCe)" class="zdu1adb9p"/></g><path class="nwbtvyygf"/><path fill="url(#iOVdENc)" class="j02-mgb1p"/><path class="fscu5zbfy"/><g filter="url(#i5ukcgl)"><path fill="url(#ircmWld)" class="u7gmkzbsy"/></g><g filter="url(#iPp0Lse)"><ellipse transform="rotate(-27.914 12.696 11.34)" class="p5yl65bxk"/><ellipse fill="url(#iNd5hue)" transform="rotate(-27.914 12.696 11.34)" class="ikoqanbap"/></g><path fill="url(#ivhXNLb)" class="m5qdgwi3b"/><path fill="url(#iAewiic)" class="m5qdgwi3b"/><path fill="url(#iXTT9Pe)" class="m5qdgwi3b"/><path fill="url(#imPtKOe)" class="m5qdgwi3b"/><path fill="url(#iJOiFMc)" class="ueun_gbha"/><path fill="url(#iDnJnzc)" class="ueun_gbha"/><g filter="url(#iGYuE7C)"><path fill="url(#ic721PZ)" class="x_787yb7u"/></g><g filter="url(#iOEcMFd)"><path fill="url(#i0TnUIe)" class="dktrq-bxa"/></g><g filter="url(#iwcxdGe)"><path class="qiff2v81d"/></g><g filter="url(#iAfhz4c)"><path class="epycsjbbs"/></g><g filter="url(#iR2aiSc)"><path class="h515piblx"/></g><defs><radialGradient id="iusfDlx" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.594)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="i1mlueb" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.674 19.536)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="i3rHTFb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.239 17.875)" gradientUnits="userSpaceOnUse"><stop class="mnp72frot"/><stop offset="1" class="l4rg4-bid"/></radialGradient><radialGradient id="ioGO8Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.597 18.153 8.92)scale(6.81742 .9881)" gradientUnits="userSpaceOnUse"><stop class="rzqjthgas"/><stop offset="1" class="ejynn6b3w"/></radialGradient><radialGradient id="iutyKpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80897 .6578 -1.95135 -5.36624 12.187 17.76)" gradientUnits="userSpaceOnUse"><stop class="i03-jcbks"/><stop offset="1" class="m27qtcbgg"/></radialGradient><radialGradient id="iWoVHje" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.106 20.242)" gradientUnits="userSpaceOnUse"><stop offset=".092" class="yartpqble"/><stop offset=".838" class="adq2qn0ak"/></radialGradient><radialGradient id="iQQWRhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.106 24.185)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="a80gjybst"/><stop offset=".937" class="vkxv1sb2j"/></radialGradient><radialGradient id="ivHRSud" cx="0" cy="0" r="1" gradientTransform="rotate(140.588 10.321 15.832)scale(2.28848 2.24827)" gradientUnits="userSpaceOnUse"><stop offset=".354" class="b5vuh20co"/><stop offset="1" class="hrswh-pmg"/></radialGradient><radialGradient id="io1vnmc" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .3353 .44041 28.086 21.342)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wyf8ygbxi"/><stop offset="1" class="i6hs9gb9s"/></radialGradient><radialGradient id="ib4I5td" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.302 12.07)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="iyulusd" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.19)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="iqJGQcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.549)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="isMJFCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 16.94)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iRXIwZz" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.98 20.811)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="i8r9Jtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12692 -1.56257 1.8364 -1.3244 16.412 19.93)" gradientUnits="userSpaceOnUse"><stop class="wbedg6bqs"/><stop offset="1" class="mu9g4n4za"/></radialGradient><radialGradient id="iAyWKGb" cx="0" cy="0" r="1" gradientTransform="rotate(61.162 -7.6 21.42)scale(2.55886 3.07062)" gradientUnits="userSpaceOnUse"><stop class="lp720zbph"/><stop offset="1" class="v7c966wuf"/></radialGradient><radialGradient id="i69ktZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.35)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i6OXeEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 24.768)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ifXEcKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.138)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iVbCzEF" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.62)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iew8KeJ" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 .398 20.95)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iswBWEm" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 9.093 13.783)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iaIR55d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 17.957 12.352)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="ixcOA0d" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.71 8.643)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="i5zVq2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 17.597 11.039)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="i0wAg5d" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.987 -.905)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="i28VVOb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 18.582 13.34)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iCj5lMc" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 8.358 9.619)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iywZB8c" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.052 14.138)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="il3Zytc" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5 -11.1796 0 15.197 5.33)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="mpwucj0za"/><stop offset=".938" class="p2sph9p8g"/><stop offset="1" class="k-3lj883k"/></radialGradient><radialGradient id="idTCjJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.616 13.713)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iAQYIzd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 15.732 13.143)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iNPZ2ob" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.216 9.548)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="is0Ut1b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9117 6.52447 -8.23836 -3.67657 14.666 6.733)" gradientUnits="userSpaceOnUse"><stop class="jy25td8rp"/><stop offset="1" class="xftsofb3t"/></radialGradient><radialGradient id="iCEtP8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29688 1.23651 0 13.133 11.202)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="hkf1_jbsj"/><stop offset="1" class="wrhkd7bsy"/></radialGradient><radialGradient id="i3y5zjb" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 14.658 15.975)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iLGRmve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 9.92 9.46)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i1Lzjbc" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.64 -5.085)scale(2.51513 4.45632)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iexQoMk" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 19.256 4.493)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="ilpNdQb" cx="0" cy="0" r="1" gradientTransform="matrix(.67168 1.19822 -2.77451 1.5553 14.245 2.901)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iqB5G8d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 15.403 5.16)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="irbm1eb" cx="0" cy="0" r="1" gradientTransform="matrix(3.2182 -5.09542 5.6452 3.56544 9.719 9.103)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iOXcBqM" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90406 17.783 8.974)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iz0gsKd" cx="0" cy="0" r="1" gradientTransform="matrix(3.24822 .37966 -.15896 1.35997 16.897 7.498)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iQMfn3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 17.332 11.436)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iBaYotd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.104 11.52)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOVdENc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 12.968 11.436)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iNd5hue" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 12.681 11.654)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iAewiic" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 19.767 11.45)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iXTT9Pe" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.128 11.994)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="imPtKOe" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.242 12.166)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iDnJnzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 10.234 12.09)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="ic721PZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 10.234 12.094)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><linearGradient id="ijs6MRb" x1="16.901" x2="15.504" y1="26.116" y2="25.813" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iVWeYuc" x1="7.199" x2="6.027" y1="25.915" y2="25.915" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="i3Sh0Me" x1="23.128" x2="23.77" y1="26" y2="25.969" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iRwJRdd" x1="22.77" x2="18.395" y1="15.985" y2="28.495" gradientUnits="userSpaceOnUse"><stop class="qm8srpk6b"/><stop offset="1" class="knnk86b5x"/></linearGradient><linearGradient id="idWSGXe" x1="16.824" x2="17.431" y1="26.486" y2="26.55" gradientUnits="userSpaceOnUse"><stop class="o_frn_b6l"/><stop offset="1" class="ohgvqyqas"/></linearGradient><linearGradient id="iHEj4Hy" x1="20.787" x2="20.787" y1="15.985" y2="16.808" gradientUnits="userSpaceOnUse"><stop offset=".165" class="oy7fe6bjb"/><stop offset="1" class="ivc982b0q"/></linearGradient><linearGradient id="igVhnne" x1="7.895" x2="11.895" y1="17.625" y2="28.875" gradientUnits="userSpaceOnUse"><stop class="e55i1-bjj"/><stop offset="1" class="rqyrdfbps"/></linearGradient><linearGradient id="iJmVmgb" x1="8.35" x2="9.063" y1="15.239" y2="19.296" gradientUnits="userSpaceOnUse"><stop class="agyv0c9kf"/><stop offset="1" class="vxg8xmb_d"/></linearGradient><linearGradient id="idKug7c" x1="7.895" x2="8.309" y1="22.563" y2="22.36" gradientUnits="userSpaceOnUse"><stop class="maqiohbml"/><stop offset="1" class="qndc1xila"/></linearGradient><linearGradient id="imWK0ae" x1="23.395" x2="21.614" y1="26.032" y2="26.032" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="iFkg6vb" x1="8.114" x2="10.395" y1="27.844" y2="26.688" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="izb8H2b" x1="15.111" x2="15.111" y1="17.386" y2="28.49" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iebJ0me" x1="17.905" x2="16.316" y1="22.093" y2="21.8" gradientUnits="userSpaceOnUse"><stop class="u4y0gibbb"/><stop offset="1" class="g49m20bpi"/></linearGradient><linearGradient id="iTohMAc" x1="25.739" x2="25.739" y1="15.682" y2="19.738" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="it2HJAe" x1="25.933" x2="25.792" y1="16.618" y2="17.821" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="iZFWRYc" x1="23.236" x2="23.363" y1="16.555" y2="16.991" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="ib01T2c" x1="26.936" x2="24.648" y1="21.125" y2="21.125" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="iL5Bq5b" x1="24.466" x2="24.847" y1="20.967" y2="20.939" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="iUPx9Mc" x1="27.084" x2="26.822" y1="20.839" y2="20.815" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="iI5Ogcb" x1="27.996" x2="23.128" y1="26.372" y2="26.372" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="mrmriqoyy"/></linearGradient><linearGradient id="ifMxTBb" x1="23.742" x2="25.663" y1="24.169" y2="24.169" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="icxHqid" x1="23.742" x2="25.663" y1="25.611" y2="25.611" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ijTeYne" x1="23.742" x2="25.663" y1="27.041" y2="27.041" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i0Q8Vce" x1="20.307" x2="17.778" y1="14.037" y2="14.037" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="i8dwqGc" x1="15.988" x2="15.149" y1="13.027" y2="13.062" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="ifgrCAc" x1="15.149" x2="15.149" y1="14.166" y2="13.701" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="imDzmIb" x1="15.149" x2="15.149" y1="11.461" y2="12.008" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iaIGhun" x1="15.565" x2="15.565" y1="14.304" y2="14.111" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="iKRfGfb" x1="13.948" x2="14.266" y1="15.737" y2="14.902" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="itDcsEd" x1="22.002" x2="10.389" y1="6.689" y2="6.689" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iatORCe" x1="18.11" x2="17.796" y1="11.49" y2="11.683" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ircmWld" x1="13.711" x2="13.398" y1="11.489" y2="11.683" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivhXNLb" x1="21.586" x2="20.379" y1="11.516" y2="13.693" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iJOiFMc" x1="9.3" x2="10.758" y1="12.22" y2="12.093" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="i0TnUIe" x1="20.566" x2="20.566" y1="11.135" y2="13.038" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><filter id="ipgmxRW" width="5.513" height="4.74" x="12.848" y="23.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2315"/></filter><filter id="ibjRhHc" width="6.102" height="1.228" x="22.791" y="16.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2315"/></filter><filter id="isiTqtd" width="1.075" height="1.075" x="25.198" y="20.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2315"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2315" result="effect2_innerShadow_4002_2315"/></filter><filter id="iPoZECe" width="5.967" height="5.967" x="12.166" y="14.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".125"/></filter><filter id="iXccOvd" width="5.813" height="5.813" x="12.243" y="14.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".25"/></filter><filter id="id2hEYd" width="5.369" height="6.076" x="23.128" y="22.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2315"/></filter><filter id="iKDkfRb" width="2.319" height=".3" x="23.592" y="23.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".05"/></filter><filter id="irrPhOb" width="2.319" height=".3" x="23.592" y="25.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".05"/></filter><filter id="irOvujb" width="2.319" height=".3" x="23.592" y="26.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".05"/></filter><filter id="ijibAzd" width="11.22" height="12.542" x="10.086" y="6.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2315"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2315" result="effect2_innerShadow_4002_2315"/></filter><filter id="iLfqbYV" width="3.747" height="4.9" x="13.134" y="10.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".5"/></filter><filter id="i1clwgd" width="2.277" height="3.3" x="14.011" y="11.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".1"/></filter><filter id="iJmoVye" width="3.718" height="1.573" x="13.29" y="14.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".05"/></filter><filter id="iA3qX8c" width="12.873" height="8.357" x="8.713" y="3.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2315"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2315" result="effect2_innerShadow_4002_2315"/></filter><filter id="ib3C9Hd" width="2.339" height="1.19" x="16.739" y="8.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2315"/></filter><filter id="iQyyiwb" width="2.339" height="1.176" x="11.482" y="8.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2315"/></filter><filter id="iGii1ge" width="6.584" height="5.992" x="9.069" y="4.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2315"/><feGaussianBlur result="effect2_foregroundBlur_4002_2315" stdDeviation=".125"/></filter><filter id="iopNlXd" width="6.319" height="5.711" x="14.991" y="4.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".125"/></filter><filter id="i8blhgc" width=".787" height=".696" x="16.598" y="10.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".05"/></filter><filter id="iPIleNe" width=".891" height=".913" x="17.437" y="11.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".1"/></filter><filter id="i5ukcgl" width=".986" height="1.04" x="12.995" y="11.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".1"/></filter><filter id="iPp0Lse" width=".913" height=".705" x="12.24" y="10.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".05"/></filter><filter id="iGYuE7C" width="1.329" height="2.379" x="9.069" y="10.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".125"/></filter><filter id="iOEcMFd" width="1.947" height="2.903" x="19.592" y="10.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".25"/></filter><filter id="iwcxdGe" width="2.405" height="1.16" x="11.402" y="8.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".125"/></filter><filter id="iAfhz4c" width="2.405" height="1.16" x="16.68" y="8.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".125"/></filter><filter id="iR2aiSc" width="5.266" height="3.006" x="16.029" y="4.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2315" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:singer-medium-dark" /></template>
<style>
.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.a80gjybst {
  stop-color: var(--svg-color--562e2e, #562E2E);
  stop-opacity: 0;
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.adq2qn0ak {
  stop-color: var(--svg-color--593031, #593031);
}

.afbr7bclm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.533h2.02");
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.agyv0c9kf {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b3i2nrbzr {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M11.739 9.263a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.b5vuh20co {
  stop-color: var(--svg-color--8b655b, #8B655B);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bn25ibyvi {
  d: path("M25.766 19.684a2.498 2.498 0 1 0 0-4.996a2.498 2.498 0 0 0 0 4.996");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c5q7122zr {
  d: path("M7.078 28.485v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.cej-hnb2p {
  d: path("M15.103 6.318a.66.66 0 0 0-.402-.137h-1.273q-.277 0-.541.044l-2.249 6.619h1.81l-.508 2.687l3.687-5.133h-1.883z");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.dktrq-bxa {
  d: path("M20.092 13.038q.059-.952.111-1.903a.956.956 0 0 1-.11 1.903");
}

.dn78wjc6c {
  d: path("M20.005 5.709c.514.177.975.536 1.267 1.051a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.75 1.75 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.513-3.342 3.38l.031 1.536a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.589-.187.912-.187c.843 0 1.58.455 1.989 1.131c.308.51.79.88 1.352 1.073");
}

.dq1_3f5_w {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m20.362 10.003l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.671-1.706 1.65-1.488c.94.209 2.004.559 2.815 1.088c1.745 1.138 1.532 3.12.613 4.085");
}

.dqa4_dciz {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 23.746v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e55i1-bjj {
  stop-color: var(--svg-color--e86b1f, #E86B1F);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.ejynn6b3w {
  stop-color: var(--svg-color--ef5945, #EF5945);
  stop-opacity: 0;
}

.epycsjbbs {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.71 9.497c-.256-.185-.897-.509-1.655-.382");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f4o-s7bti {
  d: path("m14.767 11.637l-.531 1.839c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fd9sf-bzr {
  fill: var(--svg-color--000, #000);
  d: path("M16.823 11.851c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.fscu5zbfy {
  fill: var(--svg-color--000, #000);
  d: path("M13.477 11.851a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.ft5dv1b6b {
  fill: none;
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g49m20bpi {
  stop-color: var(--svg-color--825b56, #825B56);
  stop-opacity: 0;
}

.g8jw3blad {
  d: path("m15.382 6.736l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.071.781-1.613 1.28-1.959c.14-.097.26-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.gnpanyxaf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.09h2.02");
}

.gxelnbrlp {
  d: path("M17.334 10.959a.893.893 0 0 1 .86 1.127H16.47a.896.896 0 0 1 .864-1.128");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h515piblx {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M19.343 6.692h-2.081a.483.483 0 1 1 .077-.961c.54.086 1.257.205 1.737.325c1.085.269 1.385.797 1.469 1.174a1.51 1.51 0 0 0-1.203-.538");
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hkf1_jbsj {
  stop-color: var(--svg-color--be2252, #BE2252);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hrswh-pmg {
  stop-color: var(--svg-color--673a32, #673A32);
}

.i03-jcbks {
  stop-color: var(--svg-color--d14708, #D14708);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6hs9gb9s {
  stop-color: var(--svg-color--997c73, #997C73);
  stop-opacity: 0;
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ifmu2bbjb {
  d: path("M7.078 28.485h3.87l-3.87-7.595z");
}

.ika489brf {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.799 14.854h-.001a.23.23 0 0 0-.271.046a.21.21 0 0 0-.023.27c.348.529.955.88 1.646.88c.69 0 1.297-.352 1.645-.88a.214.214 0 0 0-.023-.272a.23.23 0 0 0-.271-.045c-.39.204-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.ikoqanbap {
  cx: 12.696px;
  cy: 11.34px;
  rx: 0.39px;
  ry: 0.197px;
}

.ivc982b0q {
  stop-color: var(--svg-color--e48043, #E48043);
  stop-opacity: 0;
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j02-mgb1p {
  d: path("M12.966 10.959a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.jsbpszb3m {
  cx: 15.149px;
  cy: 17.636px;
  r: 2.734px;
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jy25td8rp {
  stop-color: var(--svg-color--e82d86, #E82D86);
}

.k-3lj883k {
  stop-color: var(--svg-color--7c4455, #7C4455);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k50-3zbvz {
  d: path("M20.01 13.602a1.64 1.64 0 0 0 .905-.309v.931c0 .893-.532 1.689-1.34 2.02a4.1 4.1 0 0 0 .345-1.18z");
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.knnk86b5x {
  stop-color: var(--svg-color--d53939, #D53939);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l4rg4-bid {
  stop-color: var(--svg-color--f6874a, #F6874A);
  stop-opacity: 0;
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.laenz-bql {
  d: path("M27.018 28.485c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.ld_9npbcv {
  d: path("M25.736 21.614a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lp720zbph {
  stop-color: var(--svg-color--73394c, #73394C);
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m27qtcbgg {
  stop-color: var(--svg-color--d14708, #D14708);
  stop-opacity: 0;
}

.m5qdgwi3b {
  d: path("M20.071 13.693q.1-1.596.185-3.192a1.61 1.61 0 0 1-.185 3.192");
}

.maqiohbml {
  stop-color: var(--svg-color--ec7046, #EC7046);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mnp72frot {
  stop-color: var(--svg-color--f6874a, #F6874A);
}

.mpwucj0za {
  stop-color: var(--svg-color--8e5c5f, #8E5C5F);
  stop-opacity: 0;
}

.mrmriqoyy {
  stop-color: var(--svg-color--744950, #744950);
}

.mu9g4n4za {
  stop-color: var(--svg-color--84605d, #84605D);
  stop-opacity: 0;
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.nwbtvyygf {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.759 10.687c-.654 0-1.205.45-1.356 1.059c-.044.174.09.34.268.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.nzlkhptrb {
  d: path("M15.118 16.298c-1.16 0-2.487.209-3.567.58l1.29 6.873c.72.325 1.497.434 2.317.434c.77 0 1.51-.073 2.19-.351l1.313-6.956c-1.05-.383-2.384-.58-3.544-.58");
}

.o_frn_b6l {
  stop-color: var(--svg-color--cc2820, #CC2820);
}

.o_mg7ubnd {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M18.882 9.372a1.85 1.85 0 0 0-.687-.411c-.304-.096-.686-.122-1.213-.057a.277.277 0 1 0 .068.55c.48-.058.776-.028.978.036c.199.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.o8fqlybaq {
  d: path("M23.128 23.372a.81.81 0 0 1 .816-.802h3.054c.745 0 1.349.589 1.349 1.315V27.4c0 .606-.503 1.096-1.124 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.314.187-.589.458-.72a.8.8 0 0 1-.457-.72c0-.314.186-.59.457-.72a.8.8 0 0 1-.457-.72a.8.8 0 0 1 .457-.72a.8.8 0 0 1-.457-.72");
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

.ohgvqyqas {
  stop-color: var(--svg-color--cc2820, #CC2820);
  stop-opacity: 0;
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oy7fe6bjb {
  stop-color: var(--svg-color--e48043, #E48043);
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p2sph9p8g {
  stop-color: var(--svg-color--7c435d, #7C435D);
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p5yl65bxk {
  cx: 12.696px;
  cy: 11.34px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pl4qbm_2r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 26.963h2.02");
}

.ptdv5_kap {
  cx: 15.149px;
  cy: 17.745px;
  r: 2.406px;
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qd55obbpm {
  d: path("M12.848 23.746v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.qiff2v81d {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.777 9.543c.257-.184.897-.509 1.655-.381");
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qm8srpk6b {
  stop-color: var(--svg-color--f98026, #F98026);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qndc1xila {
  stop-color: var(--svg-color--ec7046, #EC7046);
  stop-opacity: 0;
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qu5sukbjz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.268 11.147c.064.085-.07.189-.22.302c-.151.113-.263.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r35zuwb1w {
  d: path("M17.268 11.147c.064.085-.07.189-.22.302c-.151.113-.263.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rqyrdfbps {
  stop-color: var(--svg-color--e22f38, #E22F38);
}

.rz92qe40v {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14.748 11.833l-.59 1.838c-.102.379.14.757.484.757h.731c.344 0 .586-.384.485-.757l-.495-1.838c-.106-.407-.504-.407-.615 0");
}

.rzqjthgas {
  stop-color: var(--svg-color--ef5945, #EF5945);
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s0w4_5u6c {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.54 10.687c.654 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tfcaisbid {
  d: path("m20.362 10.003l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.671-1.706 1.65-1.488c.94.209 2.004.559 2.815 1.088c1.745 1.138 1.532 3.12.613 4.085");
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tpc0--b3t {
  d: path("M25.726 26.326a.784.784 0 0 1-.782-.711l-.67-6.428l2.975.01l-.731 6.428a.8.8 0 0 1-.792.7");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.u4y0gibbb {
  stop-color: var(--svg-color--5e302e, #5E302E);
}

.u5h71mb8p {
  d: path("M23.128 28.485v-7.267l-3.52 7.267z");
}

.u7gmkzbsy {
  d: path("M13.781 11.746c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.ubrvwpbys {
  d: path("M27.277 20.81c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.ueun_gbha {
  d: path("M10.105 10.488a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.561 1.521 1.607a78 78 0 0 1-.129-3.205");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uyyuv9bgc {
  d: path("M10.325 15.117a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.117-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.513-3.342 3.38c0 1.86.117 3.69.239 5.556");
}

.v7c966wuf {
  stop-color: var(--svg-color--754744, #754744);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vkxv1sb2j {
  stop-color: var(--svg-color--54302a, #54302A);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vxg8xmb_d {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
  stop-opacity: 0;
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wbedg6bqs {
  stop-color: var(--svg-color--84605d, #84605D);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wieq7abdc {
  d: path("M24.313 16.499h-5.58l-2.274 11.996h3.149l5.325-11.016a.685.685 0 0 0-.62-.98");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wrhkd7bsy {
  stop-color: var(--svg-color--be2252, #BE2252);
  stop-opacity: 0;
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wyf8ygbxi {
  stop-color: var(--svg-color--997c73, #997C73);
}

.x_787yb7u {
  d: path("M10.064 11.153a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xfsm94b7g {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m14.767 11.637l-.531 1.839c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.xftsofb3t {
  stop-color: var(--svg-color--d42552, #D42552);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.yartpqble {
  stop-color: var(--svg-color--865b56, #865B56);
}

.yebmocc2p {
  d: path("M5.405 16.507h6.086l2.248 11.988h-2.79l-5.88-11.528c-.086-.125-.07-.46.336-.46");
}

.yk2-i9bly {
  d: path("M15.15 15.248c-.508 0-.985-.119-1.386-.328c-.137-.07-.284.085-.198.209c.335.508.919.846 1.583.846c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.279-.198-.209a3 3 0 0 1-1.386.328");
}

.yq0mqbb7s {
  d: path("m28.214 16.526l-4.844-.02a.57.57 0 0 0-.58.579c0 .325.255.578.58.578l4.844.02a.57.57 0 0 0 .578-.578a.585.585 0 0 0-.578-.579");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zc7yzq-8f {
  d: path("M15.118 17.385c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.zdu1adb9p {
  d: path("M18.129 11.734a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zpamgqilq {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m15.382 6.736l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.804-.767-1.688c0-1.071.781-1.613 1.28-1.959c.14-.097.26-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zv7vnvb8h {
  d: path("M10.288 13.602a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
