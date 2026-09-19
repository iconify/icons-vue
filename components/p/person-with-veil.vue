<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIhr45c)"><path fill="url(#igcTSHb)" class="ickj3qbpe"/><path fill="url(#ibwLg4c)" class="ickj3qbpe"/><path fill="url(#ioxip8c)" class="ickj3qbpe"/></g><g filter="url(#i1I3PKc)"><path fill="url(#iERjKIc)" class="h8hb7bhza"/></g><path fill="url(#iNAvXpe)" class="qjef2h85n"/><path fill="url(#iP0WKyc)" class="qjef2h85n"/><path fill="url(#iG72Agd)" class="qjef2h85n"/><path fill="url(#isOfLqE)" class="qjef2h85n"/><g filter="url(#iX06cIe)"><path class="u8wlu-n5q"/></g><g filter="url(#ikIWKJd)"><path class="nj4j_or4x"/></g><g filter="url(#iJ38Wlc)"><path fill="url(#iFyj8fc)" class="s26dal06t"/><path fill="url(#iQY5ItM)" class="s26dal06t"/><path fill="url(#igupTOe)" class="s26dal06t"/></g><g filter="url(#ifRWLRd)"><path fill="url(#iroLhEc)" class="tg4-8em5x"/><path fill="url(#iBsXFEc)" class="tg4-8em5x"/><path fill="url(#iIIPLfc)" class="tg4-8em5x"/></g><g filter="url(#ivxRF5b)"><path fill="url(#i5Ntque)" class="o0g5rab3z"/><path fill="url(#iOmjTnc)" class="o0g5rab3z"/><path fill="url(#iBvHXHm)" class="o0g5rab3z"/><path fill="url(#iRYqNzb)" class="o0g5rab3z"/><path fill="url(#i7xIdSp)" class="o0g5rab3z"/></g><path fill="url(#ilql7Ie)" class="jhl6k6khu"/><path fill="url(#i96Hl6d)" class="jhl6k6khu"/><g filter="url(#iOA1smx)"><path class="w2sim3s7u"/></g><g filter="url(#iQpNgeb)"><path fill="url(#ibTWK8c)" class="y98dr8skm"/><path fill="url(#i9RYacd)" class="y98dr8skm"/></g><g filter="url(#io4x1Pc)"><path fill="url(#iiyIfla)" class="hp5l62scd"/><path fill="url(#ilu8kKd)" class="hp5l62scd"/></g><circle fill="url(#iVoNTDe)" class="yigqs335m"/><circle fill="url(#iQb4Nxv)" class="yigqs335m"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.389)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.389)" class="movji7bnz"/><circle fill="url(#ii7pBIc)" class="cv15n5ugs"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.447)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.447)" class="movji7bnz"/><path fill="url(#iG6Zi6b)" class="bl09lacsr"/><g filter="url(#iqj0Kre)"><path class="ycbfwunzr"/><path fill="url(#i3668qc)" class="opcgr88tx"/><path fill="url(#iK0Kyjb)" class="opcgr88tx"/><path fill="url(#iwM6t1d)" class="opcgr88tx"/><path fill="url(#imn1y9b)" class="opcgr88tx"/><path fill="url(#iefVPkb)" class="opcgr88tx"/></g><path fill="url(#iJlmx2d)" class="mdp_n0byo"/><g filter="url(#iXUHj8b)"><path class="skb5vkbrh"/><path fill="url(#ifO4pIc)" class="abup5ac0x"/><path fill="url(#i7XPfxe)" class="abup5ac0x"/></g><g filter="url(#ikwniHb)"><path class="ajz5yvbkc"/><path fill="url(#iLkDMNt)" class="c7rg9ewzm"/><path fill="url(#ip5qqbb)" class="c7rg9ewzm"/><path fill="url(#i8kA50c)" class="c7rg9ewzm"/><path fill="url(#i6ScMZc)" class="c7rg9ewzm"/><path fill="url(#iVeIkkb)" class="c7rg9ewzm"/></g><g filter="url(#ixpeTfb)"><path fill="url(#iyIl2Mq)" clip-rule="evenodd" class="e-5oxtbxc"/></g><g filter="url(#iIV42dL)"><path class="vpagp4b_p"/></g><g filter="url(#ioq1Age)"><path fill="url(#iGv0bfv)" class="fyul_0bdh"/><path fill="url(#iMn3LMe)" class="fyul_0bdh"/></g><g filter="url(#ib8Nqxc)"><path stroke="url(#iafllge)" class="l1myvurxm"/></g><g filter="url(#iHWmk8W)"><path stroke="url(#iLZDT7d)" class="arwbhubum"/></g><g filter="url(#i5ioAmb)"><path stroke="url(#iACsPRb)" class="y5vrmr8sr"/></g><path fill="url(#iPZEnse)" class="q0wwvs77p"/><path fill="url(#iUogEjb)" class="q0wwvs77p"/><path fill="url(#iSrMKub)" class="y09yfdb3y"/><path fill="url(#i7R79Vc)" class="y09yfdb3y"/><g filter="url(#i0Scx8c)"><path fill="url(#iVP1oic)" class="v-b2546tc"/></g><path fill="url(#iWIcERV)" class="v-b2546tc"/><path fill="url(#iHpfxzc)" class="v-b2546tc"/><path fill="url(#iMDDyqd)" class="v-b2546tc"/><path fill="url(#ig2Cf3d)" class="v-b2546tc"/><path fill="url(#i7LmDpc)" class="v-b2546tc"/><g filter="url(#iauC2hI)"><path class="x9jbh5ply"/></g><g filter="url(#iyoq6Fe)"><path fill="url(#iMu8gCe)" class="z0dpnac-p"/><path fill="url(#iE4RQte)" class="z0dpnac-p"/><path fill="url(#iCrCmxb)" class="z0dpnac-p"/></g><g filter="url(#iz4K4mc)"><path fill="url(#ia3U7Yc)" class="dnzdc-b1f"/></g><g filter="url(#itvdNrc)"><path stroke="url(#iTVlKEU)" class="pfky4bbzb"/></g><path fill="url(#i1qP2Zc)" class="w7clnebbn"/><g filter="url(#i9Kj76c)"><path fill="url(#ibsD4Ed)" class="thu4jn1pw"/><path fill="url(#iOgX3Uv)" class="thu4jn1pw"/><path fill="url(#i76mdIK)" class="thu4jn1pw"/><path fill="url(#ir65Ttz)" class="thu4jn1pw"/><path fill="url(#iRsNUNe)" class="thu4jn1pw"/></g><g filter="url(#i5C3cZb)"><path class="nosc6gb7e"/></g><g filter="url(#iWq7wdc)"><path class="jp5rj5jtk"/></g><g filter="url(#ixhZSok)"><path fill="url(#iDvrZce)" class="xj0f_2ngm"/><path fill="url(#idBucqc)" class="xj0f_2ngm"/></g><g filter="url(#iVEdMIc)"><path fill="url(#iaXyRYc)" class="qfb91cc_k"/><path fill="url(#iNpc3ud)" class="qfb91cc_k"/><path fill="url(#iDBdcbc)" class="qfb91cc_k"/><path fill="url(#ivpaAwd)" class="qfb91cc_k"/><path fill="url(#i0xuRKb)" class="qfb91cc_k"/></g><path class="nc1axlb_r"/><path fill="url(#imcba3i)" class="rk2gh1yiv"/><path class="gjhvjpkse"/><g filter="url(#ip0ccNd)"><path class="egy24zb1t"/><path fill="url(#iuYdS4c)" class="xxuw1bb-t"/></g><g filter="url(#icmdIQd)"><path fill="url(#isNtbte)" class="cxxdu2b3e"/></g><path class="meyu_3bio"/><path fill="url(#iQQ8Lbd)" class="kktrs0bxr"/><path class="upqys-nvp"/><g filter="url(#ifxBEdF)"><path fill="url(#iyioANe)" class="sf8ghjbvs"/></g><g filter="url(#ihZx4lc)"><ellipse transform="rotate(-27.914 13.53 9.912)" class="vpftu5u3o"/><ellipse fill="url(#iRb5PNV)" transform="rotate(-27.914 13.53 9.912)" class="dmqeo2vbd"/></g><path fill="url(#iiw2LEe)" class="xd46c3_oj"/><path fill="url(#iRNITmc)" class="xd46c3_oj"/><path fill="url(#iqapnde)" class="xd46c3_oj"/><path fill="url(#iYi4Wde)" class="x98kr3b-i"/><path fill="url(#irEQmCe)" class="x98kr3b-i"/><g filter="url(#iuFJGgR)"><path class="r1vbgccec"/></g><g filter="url(#iqVCHTl)"><path class="kra1dkb1d"/></g><g filter="url(#ibQnlrA)"><path class="rvzfjvbck"/></g><g filter="url(#iaifanc)"><path class="ngm38q9lz"/></g><g filter="url(#iqRPiRd)"><path fill="url(#iPkeZBc)" clip-rule="evenodd" class="re2fq0ied"/><path fill="url(#ilJRl0b)" clip-rule="evenodd" class="re2fq0ied"/></g><defs><radialGradient id="ibwLg4c" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.828 7.01)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="ioxip8c" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.61)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iNAvXpe" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.154 15.723)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="iG72Agd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 27.986)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="isOfLqE" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.142)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iQY5ItM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.78)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="igupTOe" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.64 14.62)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iBsXFEc" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.763 27.282)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="iIIPLfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.845)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="i5Ntque" cx="0" cy="0" r="1" gradientTransform="matrix(-7.18754 -5.18744 7.28549 -10.09452 19.012 22.111)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="vj4m2tb3q"/><stop offset="1" class="pcshyrb4c"/></radialGradient><radialGradient id="iOmjTnc" cx="0" cy="0" r="1" gradientTransform="rotate(144.144 6.557 11.71)scale(3.36107 1.16956)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="ospx9ybif"/><stop offset="1" class="ruijhiham"/></radialGradient><radialGradient id="iBvHXHm" cx="0" cy="0" r="1" gradientTransform="rotate(-136.548 13.54 7.47)scale(8.17891 17.4863)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="huxowdbbh"/><stop offset="1" class="ugfb6lv5r"/></radialGradient><radialGradient id="iRYqNzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91406 -.74218 .35164 -.43308 22.45 20.697)" gradientUnits="userSpaceOnUse"><stop offset=".33" class="a0lve6l9d"/><stop offset="1" class="g6l_i_bhw"/></radialGradient><radialGradient id="i7xIdSp" cx="0" cy="0" r="1" gradientTransform="rotate(155.313 6.313 9.937)scale(4.26479 1.99112)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="g5gls_bky"/><stop offset="1" class="lc_l11bld"/></radialGradient><radialGradient id="ilql7Ie" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.697 35.874)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="i9RYacd" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.152 4.9)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="ilu8kKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.282)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="iVoNTDe" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.319 11.79)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="iQb4Nxv" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.417 14.585)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="ii7pBIc" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.355 12.645)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="iG6Zi6b" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.35 19.355)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="i3668qc" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.273 20.21)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iK0Kyjb" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.48 22.986)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="iwM6t1d" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.167 9.212)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="imn1y9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.279 24.783)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="iefVPkb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.563)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="iJlmx2d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.782)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="ifO4pIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.689)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="i7XPfxe" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iLkDMNt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.267)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="ip5qqbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.955)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iyIl2Mq" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.315 16.623)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iGv0bfv" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.387 23.83)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iMn3LMe" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.217)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="iPZEnse" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 6.061 14.47)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iUogEjb" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -1.539 26.507)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iSrMKub" cx="0" cy="0" r="1" gradientTransform="matrix(1.12304 2.9706 -1.35027 .51047 10.436 11.983)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="oam7ntuck"/><stop offset="1" class="f9wu14i6k"/></radialGradient><radialGradient id="i7R79Vc" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -2.648 13.584)scale(1.04691 .91836)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="qy-o--lqz"/><stop offset="1" class="j69t0ibxx"/></radialGradient><radialGradient id="iVP1oic" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 18.791 10.924)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iWIcERV" cx="0" cy="0" r="1" gradientTransform="matrix(-.40256 6.10192 -2.24332 -.148 21.14 10.692)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iHpfxzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 13.892 9.743)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iMDDyqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 18.472 9.332)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="ig2Cf3d" cx="0" cy="0" r="1" gradientTransform="rotate(90 4.057 11.974)scale(9.62791)" gradientUnits="userSpaceOnUse"><stop offset=".643" class="t-jcjr0_x"/><stop offset="1" class="wa9ej2byx"/></radialGradient><radialGradient id="i7LmDpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.5625 -9.20461 0 16.03 9.923)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="aixxpb0ap"/><stop offset="1" class="fuignnnei"/></radialGradient><radialGradient id="iTVlKEU" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.557 -5.572)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="i1qP2Zc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.984 14.463)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iOgX3Uv" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.71897 10.1329 0 10.754 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="i76mdIK" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63265 6.43634 0 20.845 9.342)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="ir65Ttz" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10651 -1.44082 .76733 -2.187 20.09 3.066)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iRsNUNe" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 15.079 1.473)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iDvrZce" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80692 1.37358 -.3823 -1.05955 16.237 2.916)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="idBucqc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.239 -5.736)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iaXyRYc" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -7.668 86.065)scale(3.4792 1.94581)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iNpc3ud" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.056 -1.74)scale(4.28181 2.38793)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iDBdcbc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.5774 -.9364 20.492 8.38)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="ivpaAwd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.777 3.959)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="i0xuRKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.436 3.834)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="imcba3i" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.166 10.008)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iuYdS4c" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.44 .653)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQQ8Lbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.802 10.007)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iRb5PNV" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.516 10.226)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRNITmc" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.601 10.021)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iqapnde" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.962 10.566)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="irEQmCe" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.18 9.494)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="ilJRl0b" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.673 8.578)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="iIhr45c" width="21.944" height="26.818" x="4.962" y="3.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><filter id="i1I3PKc" width="12.631" height="14.916" x="9.484" y="8.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/><feGaussianBlur result="effect2_foregroundBlur_4002_3406" stdDeviation=".05"/></filter><filter id="iX06cIe" width="5.874" height="5.537" x="6.993" y="23.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".5"/></filter><filter id="ikIWKJd" width="4.98" height="4.054" x="18.51" y="24.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".5"/></filter><filter id="iJ38Wlc" width="2.973" height="2.006" x="21.47" y="23.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><filter id="ifRWLRd" width="3.281" height="2" x="20.468" y="25.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><filter id="ivxRF5b" width="13.965" height="11.381" x="9.149" y="12.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.596078 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><filter id="iOA1smx" width="10.996" height="6.432" x="11.932" y="21.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".5"/></filter><filter id="iQpNgeb" width="2.973" height="2.006" x="7.657" y="23.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><filter id="io4x1Pc" width="3.266" height="2" x="8.366" y="25.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><filter id="iqj0Kre" width="6.218" height="6.789" x="8.343" y="19.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3406" result="effect2_innerShadow_4002_3406"/></filter><filter id="iXUHj8b" width="6.218" height="6.639" x="17.574" y="19.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3406" result="effect2_innerShadow_4002_3406"/></filter><filter id="ikwniHb" width="6.702" height="6.417" x="12.683" y="20.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><filter id="ixpeTfb" width="6.703" height="6.517" x="12.632" y="20.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".15"/></filter><filter id="iIV42dL" width="3.2" height="3.2" x="14.271" y="22.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".25"/></filter><filter id="ioq1Age" width="2.35" height="2.35" x="14.892" y="23.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><filter id="ib8Nqxc" width="1.458" height="2.505" x="15.848" y="20.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".125"/></filter><filter id="iHWmk8W" width="1.723" height="1.924" x="16.939" y="24.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".125"/></filter><filter id="i5ioAmb" width="1.368" height="2.217" x="18.103" y="22.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".125"/></filter><filter id="i0Scx8c" width="10.72" height="12.542" x="10.92" y="4.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3406" result="effect2_innerShadow_4002_3406"/></filter><filter id="iauC2hI" width="3.877" height="4.9" x="13.838" y="9.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".5"/></filter><filter id="iyoq6Fe" width="2.077" height="3.1" x="14.945" y="9.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".05"/></filter><filter id="iz4K4mc" width="2.077" height="3.1" x="14.945" y="9.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".05"/></filter><filter id="itvdNrc" width="3.718" height="1.573" x="14.124" y="13.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".05"/></filter><filter id="i9Kj76c" width="12.873" height="8.356" x="9.547" y="1.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3406" result="effect2_innerShadow_4002_3406"/></filter><filter id="i5C3cZb" width="2.339" height="1.19" x="17.573" y="7.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><filter id="iWq7wdc" width="2.339" height="1.176" x="12.316" y="7.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><filter id="ixhZSok" width="6.584" height="5.992" x="9.903" y="2.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".125"/></filter><filter id="iVEdMIc" width="6.362" height="5.736" x="15.825" y="3.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".125"/></filter><filter id="ip0ccNd" width=".787" height=".696" x="17.431" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".05"/></filter><filter id="icmdIQd" width=".891" height=".913" x="18.271" y="9.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".1"/></filter><filter id="ifxBEdF" width=".986" height="1.04" x="13.829" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".1"/></filter><filter id="ihZx4lc" width=".913" height=".704" x="13.074" y="9.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".05"/></filter><filter id="iuFJGgR" width="1.329" height="2.379" x="9.951" y="9.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".125"/></filter><filter id="iqVCHTl" width="1.447" height="2.403" x="20.695" y="9.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".125"/></filter><filter id="ibQnlrA" width="2.405" height="1.16" x="12.235" y="7.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".125"/></filter><filter id="iaifanc" width="2.405" height="1.16" x="17.515" y="7.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3406" stdDeviation=".125"/></filter><filter id="iqRPiRd" width="15.448" height="4.54" x="8.283" y="2.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3406"/></filter><linearGradient id="igcTSHb" x1="26.905" x2="11.7" y1="11.486" y2="21.486" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="iERjKIc" x1="20.7" x2="10.387" y1="17.392" y2="17.392" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iP0WKyc" x1="14.887" x2="14.887" y1="30.861" y2="29.58" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="iFyj8fc" x1="23.649" x2="21.867" y1="25.783" y2="24.373" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iroLhEc" x1="22.95" x2="21.169" y1="27.367" y2="25.673" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="i96Hl6d" x1="12.653" x2="13.254" y1="29.252" y2="28.908" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="ibTWK8c" x1="7.856" x2="9.361" y1="24.267" y2="26.087" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iiyIfla" x1="9.062" x2="10.843" y1="27.366" y2="25.681" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="i8kA50c" x1="14.918" x2="16.7" y1="27.13" y2="22.861" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="i6ScMZc" x1="13.356" x2="16.981" y1="22.892" y2="23.58" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iVeIkkb" x1="17.231" x2="16.325" y1="26.892" y2="25.142" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iafllge" x1="16.477" x2="16.477" y1="20.814" y2="22.822" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iLZDT7d" x1="17.286" x2="18.153" y1="24.869" y2="26.072" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="iACsPRb" x1="18.728" x2="18.728" y1="22.4" y2="24.017" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iMu8gCe" x1="15.984" x2="16.838" y1="11.753" y2="11.753" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iE4RQte" x1="14.911" x2="15.985" y1="11.597" y2="11.656" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iCrCmxb" x1="15.984" x2="15.984" y1="12.151" y2="13.003" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="ia3U7Yc" x1="15.984" x2="15.984" y1="9.627" y2="11.308" gradientUnits="userSpaceOnUse"><stop offset=".153" class="ju3zooiog"/><stop offset="1" class="fpqt4dbfz"/></linearGradient><linearGradient id="ibsD4Ed" x1="21.347" x2="11.223" y1="5.261" y2="5.261" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="isNtbte" x1="18.944" x2="18.63" y1="10.061" y2="10.255" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyioANe" x1="14.545" x2="14.232" y1="10.061" y2="10.255" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iiw2LEe" x1="22.42" x2="21.213" y1="10.088" y2="12.264" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iYi4Wde" x1="10.134" x2="11.592" y1="10.792" y2="10.665" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iPkeZBc" x1="20.481" x2="8.544" y1="3.642" y2="7.33" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-veil" /></template>
<style>
.a0lve6l9d {
  stop-color: var(--svg-color--efab25, #EFAB25);
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.abup5ac0x {
  d: path("M23.457 22.751c.076-.155.018-.354-.098-.418c-.854-.403-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.008-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.112.293-.304.84-.336 1.135c-.152 1.231.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.aixxpb0ap {
  stop-color: var(--svg-color--ed8d0c, #ED8D0C);
  stop-opacity: 0;
}

.ajz5yvbkc {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.164c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.058 1.49.728c.17.65-.215 1.374-.884 1.494l-.457.1a.05.05 0 0 0-.03.08l.307.422c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.414a.05.05 0 0 0-.081.003l-.243.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.358-.526a.05.05 0 0 0-.033-.077l-.369-.067c-.67-.1-1.11-.75-.96-1.41");
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.arwbhubum {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.783l.906 1.18");
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bl09lacsr {
  d: path("m11.186 26.293l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.191-.717.058-.797.238c-.3.82-.082 2.137.085 3.002z");
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.c7rg9ewzm {
  d: path("M12.712 23.164c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.058 1.49.728c.17.65-.215 1.374-.884 1.494l-.457.1a.05.05 0 0 0-.03.08l.307.422c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.414a.05.05 0 0 0-.081.003l-.243.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.358-.526a.05.05 0 0 0-.033-.077l-.369-.067c-.67-.1-1.11-.75-.96-1.41");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cv15n5ugs {
  cx: 10.179px;
  cy: 21.568px;
  r: 0.762px;
}

.cxxdu2b3e {
  d: path("M18.963 10.306a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dmqeo2vbd {
  cx: 13.53px;
  cy: 9.912px;
  rx: 0.39px;
  ry: 0.197px;
}

.dnzdc-b1f {
  d: path("m15.601 9.933l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.383.52-.756l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e-5oxtbxc {
  fill-rule: evenodd;
  d: path("M13.709 24.326a.913.913 0 0 1-.753-1.107a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.302l-.03-.485v-.006q-.018-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.56a.3.3 0 0 0 .396.285l.551-.188l.007-.002c.516-.194 1.023.046 1.16.559c.14.532-.184 1.093-.687 1.183l-.466.103a.3.3 0 0 0-.179.469l.313.43l.006.007a.92.92 0 0 1-.172 1.344c-.43.298-1.012.16-1.32-.296l-.316-.422a.3.3 0 0 0-.493.017l-.247.383l-.005.008a.91.91 0 0 1-1.294.33l-.002-.001a.92.92 0 0 1-.227-1.336l.005-.006l.363-.533a.3.3 0 0 0-.196-.464l-.37-.067z");
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.egy24zb1t {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.102 9.72c.064.084-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.136.39-.05");
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f9wu14i6k {
  stop-color: var(--svg-color--de752f, #DE752F);
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fpqt4dbfz {
  stop-color: var(--svg-color--fac036, #FAC036);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuignnnei {
  stop-color: var(--svg-color--ed8d0c, #ED8D0C);
}

.fyul_0bdh {
  d: path("M15.992 25.217a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g5gls_bky {
  stop-color: var(--svg-color--ee8a27, #EE8A27);
}

.g6l_i_bhw {
  stop-color: var(--svg-color--efab25, #EFAB25);
  stop-opacity: 0;
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gjhvjpkse {
  fill: var(--svg-color--000, #000);
  d: path("M17.657 10.423c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.745h-.905a.46.46 0 0 1-.06-.235");
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.h8hb7bhza {
  d: path("M9.984 15.846c0-4.854 2.694-7.281 6.016-7.281s6.016 2.324 6.016 7.28v7.436H9.984z");
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hp5l62scd {
  d: path("M11.39 25.799c-.678-.6-1.716-.536-2.298.111l-.69.735c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.huxowdbbh {
  stop-color: var(--svg-color--f8a519, #F8A519);
  stop-opacity: 0;
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ickj3qbpe {
  d: path("M5.062 16.423c0-8.812 4.89-13.218 10.922-13.218s10.922 4.218 10.922 13.218v13.5H5.061z");
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.j69t0ibxx {
  stop-color: var(--svg-color--cb6f1e, #CB6F1E);
  stop-opacity: 0;
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jhl6k6khu {
  d: path("m13.196 29.923l-2.547-3.837l5.25-3.475l5.828 2.909l-2.922 4.403z");
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jp5rj5jtk {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.573 7.835a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.ju3zooiog {
  stop-color: var(--svg-color--fac036, #FAC036);
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kktrs0bxr {
  d: path("M13.8 9.53a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.kra1dkb1d {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.945 11.614q.059-.952.11-1.904a.956.956 0 0 1-.11 1.904");
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.l1myvurxm {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.017c.324 0 .758.376.758.86v.945");
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lc_l11bld {
  stop-color: var(--svg-color--ffa821, #FFA821);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdp_n0byo {
  d: path("m20.799 26.293l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.191.718.058.798.238c.3.82.081 2.137-.085 3.002z");
}

.meyu_3bio {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.593 9.259c-.653 0-1.205.45-1.355 1.059a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.nc1axlb_r {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.375 9.259c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34H17.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.ngm38q9lz {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.545 8.069c-.257-.184-.898-.509-1.655-.381");
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nj4j_or4x {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.964c.78-.46 1.787-.2 2.235.545l.538.852c.048.078.042.217-.074.261c-1 .38-2.053.105-2.561-.77l-.302-.651a.11.11 0 0 1 .037-.146z");
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.nosc6gb7e {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.716 7.944a1.85 1.85 0 0 0-.687-.411c-.304-.096-.685-.122-1.213-.058a.277.277 0 1 0 .068.551c.481-.059.776-.028.978.036c.199.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.o0g5rab3z {
  d: path("M9.15 20.456a11.2 11.2 0 0 1 4.31-2.047c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.062a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.oam7ntuck {
  stop-color: var(--svg-color--d78433, #D78433);
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.opcgr88tx {
  d: path("M8.528 22.751c-.076-.155-.019-.354.098-.418c.854-.403 2.333.552 3.222 1.633c.099.12.143.112.117-.035c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.354.183l.754 1.631l.133.311c.111.293.303.84.336 1.135c.152 1.231-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.ospx9ybif {
  stop-color: var(--svg-color--ffdf48, #FFDF48);
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcshyrb4c {
  stop-color: var(--svg-color--ffbe1d, #FFBE1D);
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pfky4bbzb {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.633 13.425c.39.204.855.32 1.35.32a2.9 2.9 0 0 0 1.351-.32h.001a.23.23 0 0 1 .27.045a.214.214 0 0 1 .024.272m-2.996-.317l2.934.276m-2.934-.276a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27m.295-.317l-.233.276m3.23.041l-.063-.041m.063.041l-.063-.041m.063.041c-.349.528-.956.88-1.646.88s-1.297-.351-1.646-.88m3.229-.041a1.9 1.9 0 0 1-1.583.846A1.9 1.9 0 0 1 14.4 13.7m-.062.042l.062-.042m-.062.042l.062-.042");
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q0wwvs77p {
  d: path("M20.845 12.174c.335-.011.65-.125.905-.309v.931c0 .893-.533 1.689-1.341 2.02c.17-.363.287-.759.346-1.18z");
}

.qfb91cc_k {
  d: path("m21.196 8.68l-.029-.63c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.136-.12-.368c-.256-.97.67-1.712 1.655-1.521c.974.188 2.083.517 2.903 1.051c1.744 1.138 1.439 3.189.52 4.154");
}

.qjef2h85n {
  d: path("M27 29.924v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.549 5 23.724 5 28.924v1z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qy-o--lqz {
  stop-color: var(--svg-color--cb6f1e, #CB6F1E);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r1vbgccec {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.946 9.726a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.re2fq0ied {
  fill-rule: evenodd;
  d: path("M15.972 4.355c-3.812 0-5.694 1.656-6.334 2.379a.775.775 0 0 1-1.16-1.027c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.914 7.54 2.876A.775.775 0 1 1 22.4 6.76c-.735-.758-2.556-2.405-6.428-2.405");
}

.rk2gh1yiv {
  d: path("M18.168 9.53a.892.892 0 0 1 .86 1.129h-1.724a.896.896 0 0 1 .864-1.128");
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruijhiham {
  stop-color: var(--svg-color--ffdf48, #FFDF48);
  stop-opacity: 0;
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.rvzfjvbck {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.61 8.115c.257-.185.898-.509 1.656-.382");
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s26dal06t {
  d: path("M21.48 25.286c.063-.898.843-1.586 1.721-1.535l.99.06c.121 0 .162.157.149.206c-.176.967-.961 1.703-2 1.633l-.768-.097a.11.11 0 0 1-.102-.118z");
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sf8ghjbvs {
  d: path("M14.615 10.318c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.skb5vkbrh {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.751c.076-.155.018-.354-.098-.418c-.854-.403-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.008-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.112.293-.304.84-.336 1.135c-.152 1.231.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t-jcjr0_x {
  stop-color: var(--svg-color--ffb838, #FFB838);
  stop-opacity: 0;
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.tg4-8em5x {
  d: path("M20.61 25.799c.678-.6 1.716-.536 2.297.111l.69.735c.063.067.083.205-.023.27c-.91.563-1.996.492-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.thu4jn1pw {
  d: path("M20.839 4.281c.514.177.976.536 1.267 1.051A2.37 2.37 0 0 1 22 7.86a1.56 1.56 0 0 0-.27.874V9.92a1.7 1.7 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.38-1.432h-1.4A2.42 2.42 0 0 1 16.15 5.17a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.513-3.341 3.38l.03 1.537a1.7 1.7 0 0 0-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.187.912-.187c.843 0 1.58.456 1.99 1.131c.307.51.79.88 1.352 1.073");
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.u8wlu-n5q {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.135c.879-.051 1.658.636 1.72 1.534l.009.116c.31.044.61.175.862.397l.107.114a.11.11 0 0 1 .01.15l-.42.582c-.665.763-1.75.834-2.66.271c-.064-.05-.086-.203-.024-.27l.69-.735q.136-.151.302-.26c-.906-.06-1.574-.75-1.735-1.633c-.013-.05.028-.207.15-.207z");
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ugfb6lv5r {
  stop-color: var(--svg-color--f8a519, #F8A519);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.upqys-nvp {
  fill: var(--svg-color--000, #000);
  d: path("M14.31 10.423a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v-b2546tc {
  d: path("M11.159 13.689a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.117 3.691.239 5.557");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vj4m2tb3q {
  stop-color: var(--svg-color--ffd336, #FFD336);
}

.vpagp4b_p {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.348a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.vpftu5u3o {
  cx: 13.53px;
  cy: 9.912px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.w2sim3s7u {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.4c.096.053.144.219.081.348l-.668 1.39c-.181.388-.526.926-.809 1.177c-.687.638-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.325-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.003l-.201.312a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.415l.298-.438a.042.042 0 0 0-.028-.065l-.307-.055a.97.97 0 0 1-.8-1.173a.97.97 0 0 1 1.25-.708l.515.176a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.664.81-1.062v.467c0 .028.028.048.055.04l.458-.157q.112-.042.223-.058l.035-.084l1.044.854c.063-.13.19-.198.295-.153c.711.328.494-.417.288.729c-.022.122.015.129.098.029c.74-.9 1.97-1.695 2.682-1.36");
}

.w7clnebbn {
  d: path("M15.984 13.82c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.508.919.846 1.584.846c.664 0 1.248-.338 1.583-.846c.086-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wa9ej2byx {
  stop-color: var(--svg-color--e8891d, #E8891D);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x98kr3b-i {
  d: path("M10.93 9.065a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.x9jbh5ply {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.497 10.405l-.634 1.838c-.109.378.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.542-.407-.662 0");
}

.xd46c3_oj {
  d: path("M20.906 12.265c.065-1.065.129-2.128.184-3.192a1.61 1.61 0 0 1-.184 3.191");
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xj0f_2ngm {
  d: path("m16.216 5.308l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.513-3.341 3.38v.274c-.34-.258-.768-.804-.768-1.687c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.18.33-.253q.047-.046.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xxuw1bb-t {
  d: path("M18.102 9.72c.064.084-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.136.39-.05");
}

.y09yfdb3y {
  d: path("M11.122 12.174a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y5vrmr8sr {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.564c.307.135.83.616.461 1.453");
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.y98dr8skm {
  d: path("M10.52 25.286c-.063-.898-.843-1.586-1.721-1.535l-.99.06c-.121 0-.163.157-.15.206c.177.967.962 1.703 2 1.633l.769-.097a.11.11 0 0 0 .102-.118z");
}

.ycbfwunzr {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.751c-.076-.155-.019-.354.098-.418c.854-.403 2.333.552 3.222 1.633c.099.12.143.112.117-.035c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.354.183l.754 1.631l.133.311c.111.293.303.84.336 1.135c.152 1.231-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yigqs335m {
  cx: 9.168px;
  cy: 20.49px;
  r: 0.762px;
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z0dpnac-p {
  d: path("m15.601 10.21l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
