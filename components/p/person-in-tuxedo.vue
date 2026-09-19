<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iDFerFe)" class="fgk-5hbhi"/><path fill="url(#i0bnV8d)" class="fgk-5hbhi"/><path fill="url(#iKSChfb)" class="fgk-5hbhi"/><path fill="url(#iOzabcD)" class="fgk-5hbhi"/><path fill="url(#i92qmGe)" class="fgk-5hbhi"/><path fill="url(#iP7xtVK)" class="jockr5brf"/><path fill="url(#iKXZx0b)" class="jockr5brf"/><g filter="url(#iJsOZ8d)"><path fill="url(#iSGtb3c)" class="vscmdxbrb"/><path fill="url(#iVQ1hjc)" class="vscmdxbrb"/></g><path fill="url(#iEQBJ3d)" class="k8ix0jbxx"/><g filter="url(#iwq2m2Z)"><path fill="url(#iEjPYgX)" class="mj9a-09qg"/><path fill="url(#iLbvW7l)" class="mj9a-09qg"/></g><g filter="url(#i4nt1zT)"><path clip-rule="evenodd" class="wwr4rtl1i"/></g><path fill="url(#iimOnxa)" class="hlyur2f6y"/><path fill="url(#ikgV5Dc)" class="hlyur2f6y"/><path fill="url(#iuTRW6b)" class="hlyur2f6y"/><path fill="url(#iRSaCgd)" class="hlyur2f6y"/><path fill="url(#ioxPLSd)" class="nfw87zbhc"/><path fill="url(#iCIUKvd)" class="nfw87zbhc"/><path fill="url(#iv7Upid)" class="nfw87zbhc"/><path fill="url(#iqxFvob)" class="nfw87zbhc"/><g filter="url(#iYLo9Cc)"><path fill="url(#iWg0yye)" class="ceclfgb0n"/></g><g filter="url(#i5o4Pom)"><path fill="url(#imi6qCe)" class="svt_7-pew"/></g><path fill="url(#iKiHcbb)" class="svt_7-pew"/><path fill="url(#i6QxIpL)" class="svt_7-pew"/><path fill="url(#iZVvX9d)" class="svt_7-pew"/><g filter="url(#iewkAhc)"><path class="z8qin0otf"/></g><g filter="url(#iHmBpQc)"><circle class="dr-k41b2k"/></g><g filter="url(#iaCTDsb)"><circle class="uy8ok031y"/></g><g filter="url(#izGnKld)"><circle fill="url(#iQWVlgf)" class="smrxvvbzr"/></g><g filter="url(#iddWJad)"><circle fill="url(#i1xsAGY)" class="cnk20mb3o"/></g><rect fill="url(#i3OiSrS)" class="cydfracdw"/><rect fill="url(#iihO6Fe)" class="cydfracdw"/><rect fill="url(#iSuZekc)" class="cydfracdw"/><g filter="url(#iTEBAcb)"><path fill="url(#iHrAMlb)" class="yfb2pac1x"/></g><path fill="url(#iDvp61c)" class="yfb2pac1x"/><g filter="url(#irEHwSb)"><path class="dyuw2qbvm"/><path fill="url(#i0fii8l)" class="fl8jdgkvu"/><path fill="url(#i2xtQ7c)" class="fl8jdgkvu"/><path fill="url(#iQbtvjb)" class="fl8jdgkvu"/></g><g filter="url(#iCfEbYs)"><circle fill="url(#in03t1b)" class="x5prydbjk"/><circle fill="url(#iHjr1Ec)" class="x5prydbjk"/></g><path fill="url(#iVtscgc)" class="lucb-9bjw"/><path fill="url(#iSZ11wc)" class="lucb-9bjw"/><path fill="url(#ifJYxuc)" class="hk3ldjv7e"/><path fill="url(#imXdBdd)" class="hk3ldjv7e"/><g filter="url(#il79qid)"><path fill="url(#itm5eVX)" class="hkkr7ibow"/></g><path fill="url(#iyy3qTc)" class="hkkr7ibow"/><path fill="url(#iqUPXhK)" class="hkkr7ibow"/><path fill="url(#iVDOwqb)" class="hkkr7ibow"/><path fill="url(#iNQCeKc)" class="hkkr7ibow"/><g filter="url(#i6az16b)"><path class="mvs5rvbgt"/></g><g filter="url(#ielyDhe)"><path fill="url(#iTBhTXB)" class="yxafb4bpe"/><path fill="url(#iW86URd)" class="yxafb4bpe"/><path fill="url(#ijax8qb)" class="yxafb4bpe"/></g><g filter="url(#i3Lwpae)"><path fill="url(#i0Yx1Rd)" class="sstz6ibqe"/></g><g filter="url(#iRkmvpE)"><path stroke="url(#i0XISJd)" class="fk2xzwbbz"/></g><path fill="url(#ijrqNlc)" class="uim0yhb6b"/><g filter="url(#izKCSJe)"><path fill="url(#iL3kG7b)" class="d782khbtq"/><path fill="url(#irTwbvb)" class="d782khbtq"/><path fill="url(#i48kGvd)" class="d782khbtq"/><path fill="url(#i40AQ8c)" class="d782khbtq"/><path fill="url(#iNb98Tc)" class="d782khbtq"/></g><g filter="url(#iPQYdme)"><path class="bu-jebbgj"/></g><g filter="url(#iTreyte)"><path class="o6p_w_bsk"/></g><g filter="url(#ixHcJia)"><path fill="url(#iNxZIHr)" class="nkqj5bavz"/><path fill="url(#iG7LI4d)" class="nkqj5bavz"/></g><g filter="url(#inEBNxi)"><path fill="url(#iAJzLid)" class="b-ew7yuuk"/><path fill="url(#i9vnnsc)" class="b-ew7yuuk"/><path fill="url(#iA7a5Lc)" class="b-ew7yuuk"/><path fill="url(#ie66K3d)" class="b-ew7yuuk"/><path fill="url(#illfqcb)" class="b-ew7yuuk"/></g><path class="svrsgibir"/><path fill="url(#i0aBJKV)" class="no1skdbwy"/><path class="upjhl4bux"/><g filter="url(#iGVwprd)"><path class="bv5bhabuv"/><path fill="url(#iiCW1Zd)" class="ofpmqybwj"/></g><g filter="url(#ipo8lIc)"><path fill="url(#ioU3F7b)" class="pph1-xbam"/></g><path class="widjkbcoe"/><path fill="url(#iNNCRfC)" class="aayum4wsy"/><path class="h83vx0b-i"/><g filter="url(#iot1Ayd)"><path fill="url(#itWlx0U)" class="t8-bz21_i"/></g><g filter="url(#i2HVsle)"><ellipse transform="rotate(-27.914 13.508 9.923)" class="wmc0th44q"/><ellipse fill="url(#ihc4Wxk)" transform="rotate(-27.914 13.508 9.923)" class="u3w8sgb3u"/></g><path fill="url(#iyzGADd)" class="y4i1zob7f"/><path fill="url(#iDbE7nb)" class="y4i1zob7f"/><path fill="url(#ixVjpKc)" class="y4i1zob7f"/><path fill="url(#iFakXNd)" class="p4zw47j7a"/><path fill="url(#iTFzAve)" class="p4zw47j7a"/><g filter="url(#igRizfe)"><path class="qeazg3qrr"/></g><g filter="url(#ifsiQJd)"><path class="kpg8-mbcq"/></g><g filter="url(#iNUQ9cc)"><path class="sjy8iabev"/></g><g filter="url(#itYQhwx)"><path class="v40v-rb3n"/></g><defs><radialGradient id="iDFerFe" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.315)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="i0bnV8d" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.77 10.813)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="iKSChfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.226)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iP7xtVK" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.242 2.61)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iKXZx0b" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.127)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="iSGtb3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.383)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="iEQBJ3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.539)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="iEjPYgX" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.506)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iLbvW7l" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.349 13.025)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="ikgV5Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.104 8.356)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="iuTRW6b" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.648)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="iCIUKvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.742)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iv7Upid" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.382)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="imi6qCe" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.075 11.856)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="iKiHcbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.263)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="i6QxIpL" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.322)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="iZVvX9d" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.659 20.617)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iQWVlgf" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.875 16.043)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="i1xsAGY" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.493 14.54)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iihO6Fe" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 6.249 11.68)scale(2.36263 1.82529)" gradientUnits="userSpaceOnUse"><stop class="wdszzbb5h"/><stop offset="1" class="y20wtkswp"/></radialGradient><radialGradient id="iSuZekc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.125 1.0835 0 16.012 18.78)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="rm80ez1_k"/><stop offset="1" class="wape09b3k"/></radialGradient><radialGradient id="iHrAMlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.73)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iDvp61c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.105)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="i2xtQ7c" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.438 6.855)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="iQbtvjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.96)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="in03t1b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.375 12.583)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iHjr1Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="iVtscgc" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 6.046 14.467)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iSZ11wc" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -1.56 26.49)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="ifJYxuc" cx="0" cy="0" r="1" gradientTransform="matrix(1.33305 3.92345 -1.7834 .60594 10.414 11.993)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="imXdBdd" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -2.666 13.574)scale(1.04691 .91836)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="itm5eVX" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 18.769 10.934)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iyy3qTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.27831 12.9416 0 15.767 17.27)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="hgknsbpup"/><stop offset="1" class="tv9ayrore"/></radialGradient><radialGradient id="iqUPXhK" cx="0" cy="0" r="1" gradientTransform="matrix(-.40256 6.10192 -2.24332 -.148 21.119 10.703)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iVDOwqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 13.87 9.754)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="iNQCeKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 18.45 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="i0XISJd" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.556 -5.548)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="ijrqNlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.961 14.474)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="irTwbvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.71897 10.1329 0 10.732 9.353)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="i48kGvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63265 6.43634 0 20.822 9.353)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="i40AQ8c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10651 -1.44082 .76733 -2.187 20.068 3.076)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iNb98Tc" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 15.056 1.484)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iNxZIHr" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80692 1.37358 -.3823 -1.05955 16.215 2.926)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iG7LI4d" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.237 -5.71)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iAJzLid" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -7.725 85.975)scale(3.4792 1.94581)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="i9vnnsc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.048 -1.728)scale(4.28181 2.38793)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iA7a5Lc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.5774 -.9364 20.47 8.391)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="ie66K3d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.755 3.97)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="illfqcb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.414 3.845)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="i0aBJKV" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.143 10.018)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iiCW1Zd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.432 .664)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNNCRfC" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.78 10.019)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ihc4Wxk" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.493 10.238)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDbE7nb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.579 10.032)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="ixVjpKc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.94 10.577)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iTFzAve" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.164 9.49)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="iJsOZ8d" width="4.081" height="11.683" x="5.07" y="18.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/></filter><filter id="iwq2m2Z" width="5.909" height="14.117" x="12.858" y="15.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/></filter><filter id="i4nt1zT" width="7.13" height="5.229" x="12.285" y="16.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".3"/></filter><filter id="iYLo9Cc" width="7.239" height="14.645" x="9.195" y="15.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".5"/></filter><filter id="i5o4Pom" width="5.917" height="14.31" x="10.326" y="15.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3320" result="effect2_innerShadow_4002_3320"/></filter><filter id="iewkAhc" width="6.504" height="14.261" x="15.345" y="15.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3320" result="effect2_innerShadow_4002_3320"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3320" result="effect3_innerShadow_4002_3320"/></filter><filter id="iHmBpQc" width="2" height="2" x="14.731" y="24.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".25"/></filter><filter id="iaCTDsb" width="2" height="2" x="14.731" y="21.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".25"/></filter><filter id="izGnKld" width="1.05" height="1.05" x="15.504" y="25.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/></filter><filter id="iddWJad" width="1.05" height="1.05" x="15.504" y="22.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/></filter><filter id="iTEBAcb" width="2.465" height="2.95" x="16.029" y="17.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3320" result="effect2_innerShadow_4002_3320"/></filter><filter id="irEHwSb" width="2.365" height="2.9" x="13.731" y="17.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/></filter><filter id="iCfEbYs" width="1.717" height="1.717" x="15.204" y="17.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/></filter><filter id="il79qid" width="10.72" height="12.542" x="10.898" y="4.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3320" result="effect2_innerShadow_4002_3320"/></filter><filter id="i6az16b" width="3.877" height="4.9" x="13.815" y="9.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".5"/></filter><filter id="ielyDhe" width="2.077" height="3.1" x="14.923" y="9.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".05"/></filter><filter id="i3Lwpae" width="2.077" height="3.1" x="14.923" y="9.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".05"/></filter><filter id="iRkmvpE" width="3.718" height="1.573" x="14.102" y="13.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".05"/></filter><filter id="izKCSJe" width="12.873" height="8.356" x="9.525" y="1.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3320" result="effect2_innerShadow_4002_3320"/></filter><filter id="iPQYdme" width="2.339" height="1.19" x="17.55" y="7.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.215686 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/></filter><filter id="iTreyte" width="2.339" height="1.176" x="12.294" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.215686 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3320"/></filter><filter id="ixHcJia" width="6.584" height="5.992" x="9.88" y="2.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".125"/></filter><filter id="inEBNxi" width="6.362" height="5.736" x="15.802" y="3.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".125"/></filter><filter id="iGVwprd" width=".787" height=".696" x="17.409" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".05"/></filter><filter id="ipo8lIc" width=".891" height=".913" x="18.249" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".1"/></filter><filter id="iot1Ayd" width=".986" height="1.04" x="13.806" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".1"/></filter><filter id="i2HVsle" width=".913" height=".705" x="13.052" y="9.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".05"/></filter><filter id="igRizfe" width="1.329" height="2.379" x="9.929" y="9.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".125"/></filter><filter id="ifsiQJd" width="1.447" height="2.403" x="20.673" y="9.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".125"/></filter><filter id="iNUQ9cc" width="2.105" height=".86" x="12.363" y="7.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".075"/></filter><filter id="itYQhwx" width="2.105" height=".86" x="17.642" y="7.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3320" stdDeviation=".075"/></filter><linearGradient id="iOzabcD" x1="23.131" x2="22.971" y1="29.905" y2="29.905" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="i92qmGe" x1="8.858" x2="9.061" y1="29.905" y2="29.905" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iVQ1hjc" x1="9.19" x2="7.596" y1="29.913" y2="29.913" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="iimOnxa" x1="14.705" x2="13.268" y1="19.976" y2="16.851" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="dpuybmbgp"/></linearGradient><linearGradient id="iRSaCgd" x1="15.518" x2="15.209" y1="20.054" y2="19.937" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="ioxPLSd" x1="16.799" x2="18.471" y1="19.992" y2="17.117" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="syt8fxg1a"/></linearGradient><linearGradient id="iqxFvob" x1="16.486" x2="16.713" y1="19.793" y2="19.703" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="iWg0yye" x1="12.815" x2="12.815" y1="16.773" y2="29.418" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="i3OiSrS" x1="17.033" x2="14.075" y1="18.382" y2="17.757" gradientUnits="userSpaceOnUse"><stop class="a-reuebjz"/><stop offset=".989" class="n35s_9bkr"/></linearGradient><linearGradient id="i0fii8l" x1="15.205" x2="14.838" y1="19.429" y2="18.976" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="iTBhTXB" x1="15.961" x2="16.816" y1="11.763" y2="11.763" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iW86URd" x1="14.889" x2="15.963" y1="11.608" y2="11.667" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="ijax8qb" x1="15.961" x2="15.961" y1="12.162" y2="13.014" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="i0Yx1Rd" x1="15.961" x2="15.961" y1="9.721" y2="11.212" gradientUnits="userSpaceOnUse"><stop class="oarh-ibsj"/><stop offset="1" class="n6kw8icqf"/></linearGradient><linearGradient id="iL3kG7b" x1="21.325" x2="11.201" y1="5.272" y2="5.272" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="ioU3F7b" x1="18.921" x2="18.608" y1="10.072" y2="10.265" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itWlx0U" x1="14.523" x2="14.209" y1="10.072" y2="10.265" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyzGADd" x1="22.398" x2="21.191" y1="10.099" y2="12.275" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iFakXNd" x1="10.112" x2="11.57" y1="10.803" y2="10.676" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-tuxedo" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a-reuebjz {
  stop-color: var(--svg-color--dd922e, #DD922E);
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.aayum4wsy {
  d: path("M13.777 9.542a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b-ew7yuuk {
  d: path("m21.174 8.691l-.03-.631c-.01-.763-.64-1.393-1.404-1.425h-1.4c-.89 0-1.7-.486-2.125-1.26c0 0-.058-.136-.12-.368c-.256-.97.671-1.713 1.656-1.522c.973.19 2.082.517 2.902 1.052c1.745 1.138 1.44 3.189.521 4.154");
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bu-jebbgj {
  fill: var(--svg-color--c05226, #C05226);
  d: path("M19.694 7.955a1.85 1.85 0 0 0-.687-.411c-.305-.096-.686-.122-1.213-.057a.277.277 0 1 0 .068.55c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.bv5bhabuv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.08 9.73c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.05");
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.ceclfgb0n {
  d: path("M11.242 18.34c-.03-1.011.55-1.42.819-1.502l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.015c.047.082-.05.176-.132.12c-2.75-1.881-4.776-3.354-5.094-8.18a.19.19 0 0 1 .174-.198c.297-.02.56-.044.747-.061a.19.19 0 0 0 .171-.191c-.01-.53-.02-1.532-.046-2.431");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cnk20mb3o {
  cx: 16.004px;
  cy: 22.567px;
  r: 0.5px;
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.cydfracdw {
  width: 3.875px;
  height: 4.5px;
  x: 14.075px;
  y: 14.281px;
  rx: 1.938px;
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d782khbtq {
  d: path("M20.816 4.292a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.875v1.188a1.75 1.75 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418H14.24c-1.845 0-3.34 1.512-3.34 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.445a2.35 2.35 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.188.912-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dpuybmbgp {
  stop-color: var(--svg-color--9b7388, #9B7388);
}

.dr-k41b2k {
  cx: 15.731px;
  cy: 25.848px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.dyuw2qbvm {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.475l1.813 1.25l-1.795 1.26a.246.246 0 0 1-.389-.188c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.178");
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fgk-5hbhi {
  d: path("M5.07 26.41c0-5.797 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.823 10.5 10.62v3.496H5.07z");
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fk2xzwbbz {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.61 13.436c.39.203.855.32 1.351.32c.501 0 .961-.117 1.351-.32a.23.23 0 0 1 .271.044a.214.214 0 0 1 .024.273m-2.996-.317l2.934.276m-2.935-.276a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27m.294-.317l-.232.276m3.23.041h-.001l-.062-.041m.062.041l-.062-.041m.062.041c-.348.528-.955.88-1.646.88c-.69 0-1.297-.352-1.645-.88m3.229-.041a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.062.042l.062-.042m-.062.042v-.001l.062-.041");
}

.fl8jdgkvu {
  d: path("m14.133 17.475l1.813 1.25l-1.795 1.26a.246.246 0 0 1-.389-.188c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.178");
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h83vx0b-i {
  fill: var(--svg-color--000, #000);
  d: path("M14.288 10.434a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.hgknsbpup {
  stop-color: var(--svg-color--d1724d, #D1724D);
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hk3ldjv7e {
  d: path("M11.1 12.185a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.341 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.hkkr7ibow {
  d: path("M11.136 13.7a3.916 3.916 0 0 0 3.886 3.405h1.887a3.916 3.916 0 0 0 3.885-3.405c.118-1.884.237-3.76.325-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418H14.24c-1.845 0-3.34 1.512-3.34 3.379c0 1.86.115 3.691.237 5.557");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hlyur2f6y {
  d: path("M14.41 20.277c-1.185-1.235-1.403-3.047-1.367-3.871h2.969l.035 2.222l-.773 1.52c-.148.308-.608.394-.863.129");
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jockr5brf {
  d: path("M23.099 18.23a10.68 10.68 0 0 1 3.831 8.18v3.496H23.1z");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.k8ix0jbxx {
  d: path("M8.901 18.23a10.68 10.68 0 0 0-3.831 8.18v3.496H8.9z");
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

.kpg8-mbcq {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.923 11.625q.059-.953.11-1.904a.956.956 0 0 1-.11 1.903");
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
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

.lucb-9bjw {
  d: path("M20.823 12.185a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.019a4.1 4.1 0 0 0 .345-1.18z");
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mj9a-09qg {
  d: path("M18.767 16.057a10.3 10.3 0 0 0-2.337-.268h-.86q-1.194.002-2.312.262v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.461 2.57-4.258 2.57-8.433z");
}

.mvs5rvbgt {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.475 10.416l-.635 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.114-.408-.543-.408-.662 0");
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.n35s_9bkr {
  stop-color: var(--svg-color--cb752e, #CB752E);
}

.n6kw8icqf {
  stop-color: var(--svg-color--f9bc34, #F9BC34);
  stop-opacity: 0;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nfw87zbhc {
  d: path("M17.598 20.277c1.186-1.235 1.404-3.047 1.367-3.871h-2.968l-.036 2.222l.774 1.52c.148.308.608.394.863.129");
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nkqj5bavz {
  d: path("m16.194 5.319l-.066-.137a.66.66 0 0 0-.616-.418H14.24c-1.845 0-3.34 1.512-3.34 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.781-1.613 1.28-1.959c.14-.097.259-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.893v1.485z");
}

.no1skdbwy {
  d: path("M18.145 9.542a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o6p_w_bsk {
  fill: var(--svg-color--c05226, #C05226);
  d: path("M12.55 7.846a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.oarh-ibsj {
  stop-color: var(--svg-color--f9bc34, #F9BC34);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpmqybwj {
  d: path("M18.08 9.73c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.05");
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.p4zw47j7a {
  d: path("M10.907 9.076a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pph1-xbam {
  d: path("M18.94 10.316a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
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

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.qeazg3qrr {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.924 9.737a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rm80ez1_k {
  stop-color: var(--svg-color--be6439, #BE6439);
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.sjy8iabev {
  stroke: var(--svg-color--c96754, #C96754);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.588 8.126c.257-.185.898-.51 1.655-.382");
}

.smrxvvbzr {
  cx: 16.004px;
  cy: 25.575px;
  r: 0.5px;
}

.sstz6ibqe {
  d: path("m15.58 10.027l-.532 1.838c-.109.378.152.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.svrsgibir {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.352 9.27c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.371-1.127");
}

.svt_7-pew {
  d: path("M11.709 17.543c-.032-1.094.595-1.537.886-1.626l.668-.07v5.815c0 3.873 1.453 6.262 2.712 8.087c.063.091-.047.201-.138.139c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.048.808-.066c.107-.01.188-.1.186-.207c-.011-.574-.023-1.658-.05-2.631");
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.syt8fxg1a {
  stop-color: var(--svg-color--ddc5cf, #DDC5CF);
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.t8-bz21_i {
  d: path("M14.593 10.329c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tv9ayrore {
  stop-color: var(--svg-color--f19a3c, #F19A3C);
  stop-opacity: 0;
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.u3w8sgb3u {
  cx: 13.508px;
  cy: 9.923px;
  rx: 0.39px;
  ry: 0.197px;
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.uim0yhb6b {
  d: path("M15.961 13.831c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.918.846 1.583.846s1.249-.339 1.584-.846c.086-.13-.061-.28-.198-.21a3 3 0 0 1-1.386.329");
}

.upjhl4bux {
  fill: var(--svg-color--000, #000);
  d: path("M17.634 10.434c0-.284.227-.511.511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.uy8ok031y {
  cx: 15.731px;
  cy: 22.7px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v40v-rb3n {
  stroke: var(--svg-color--c96754, #C96754);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.522 8.08c-.257-.185-.897-.51-1.655-.382");
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vscmdxbrb {
  d: path("M8.901 18.23a10.69 10.69 0 0 0-3.831 8.185v3.498H8.9z");
}

.wape09b3k {
  stop-color: var(--svg-color--be6439, #BE6439);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wdszzbb5h {
  stop-color: var(--svg-color--e1a61f, #E1A61F);
}

.widjkbcoe {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.57 9.27c-.653 0-1.204.45-1.355 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .228-.272A1.4 1.4 0 0 0 13.57 9.27");
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wmc0th44q {
  cx: 13.508px;
  cy: 9.923px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wwr4rtl1i {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.68c-.037.825.18 2.636 1.367 3.871c.255.266.715.18.863-.129l.73-1.435l.731 1.435c.149.309.608.395.863.13c1.186-1.236 1.404-3.047 1.368-3.872z");
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x5prydbjk {
  cx: 16.012px;
  cy: 18.695px;
  r: 0.809px;
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.y20wtkswp {
  stop-color: var(--svg-color--e1a61f, #E1A61F);
  stop-opacity: 0;
}

.y4i1zob7f {
  d: path("M20.883 12.275q.1-1.596.185-3.191a1.61 1.61 0 0 1-.185 3.191");
}

.yfb2pac1x {
  d: path("m17.892 17.475l-1.813 1.25l1.795 1.26c.159.11.378.006.388-.188c.041-.791.041-1.57.008-2.144a.239.239 0 0 0-.378-.178");
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.yxafb4bpe {
  d: path("m15.58 10.22l-.532 1.838c-.109.379.152.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.z8qin0otf {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.316 17.543c.031-1.094-.595-1.537-.887-1.626l-.668-.07v5.815c0 3.873-1.388 6.264-2.648 8.09c-.062.09.047.2.139.138c2.976-2.036 4.851-4.005 5.196-9.228a.203.203 0 0 0-.188-.215c-.321-.02-.607-.048-.809-.066a.204.204 0 0 1-.185-.207c.011-.574.022-1.658.05-2.631");
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
