<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iDFerFe)" class="fgk-5hbhi"/><path fill="url(#i0bnV8d)" class="fgk-5hbhi"/><path fill="url(#iKSChfb)" class="fgk-5hbhi"/><path fill="url(#iOzabcD)" class="fgk-5hbhi"/><path fill="url(#i92qmGe)" class="fgk-5hbhi"/><path fill="url(#iP7xtVK)" class="jockr5brf"/><path fill="url(#iKXZx0b)" class="jockr5brf"/><g filter="url(#iugGZ3V)"><path fill="url(#iSGtb3c)" class="vscmdxbrb"/><path fill="url(#iVQ1hjc)" class="vscmdxbrb"/></g><path fill="url(#iEQBJ3d)" class="k8ix0jbxx"/><g filter="url(#iA3YdUd)"><path fill="url(#iEjPYgX)" class="mj9a-09qg"/><path fill="url(#iLbvW7l)" class="mj9a-09qg"/></g><g filter="url(#inGMnAc)"><path class="ti_8km29h"/></g><path fill="url(#ivWFWhb)" class="hlyur2f6y"/><path fill="url(#ikgV5Dc)" class="hlyur2f6y"/><path fill="url(#iuTRW6b)" class="hlyur2f6y"/><path fill="url(#iRSaCgd)" class="hlyur2f6y"/><path fill="url(#i5AU1ke)" class="nfw87zbhc"/><path fill="url(#iCIUKvd)" class="nfw87zbhc"/><path fill="url(#iv7Upid)" class="nfw87zbhc"/><path fill="url(#iqxFvob)" class="nfw87zbhc"/><g filter="url(#i0Dkjqc)"><path fill="url(#iWg0yye)" class="ceclfgb0n"/></g><g filter="url(#imMCbJb)"><path fill="url(#imi6qCe)" class="svt_7-pew"/></g><path fill="url(#iKiHcbb)" class="svt_7-pew"/><path fill="url(#i6QxIpL)" class="svt_7-pew"/><path fill="url(#iZVvX9d)" class="svt_7-pew"/><g filter="url(#iScKE1c)"><path class="z8qin0otf"/></g><g filter="url(#i5T9Yvd)"><circle class="dr-k41b2k"/></g><g filter="url(#ic7fv9c)"><circle class="uy8ok031y"/></g><g filter="url(#iEgXFzc)"><circle fill="url(#iQWVlgf)" class="smrxvvbzr"/></g><g filter="url(#iAEH77b)"><circle fill="url(#i1xsAGY)" class="cnk20mb3o"/></g><rect fill="url(#iRlk2ke)" class="cydfracdw"/><rect fill="url(#igO2Lpb)" class="cydfracdw"/><rect fill="url(#iFAZiTi)" class="cydfracdw"/><rect fill="url(#i3wY97d)" class="cydfracdw"/><g filter="url(#iJLLfwG)"><path fill="url(#iHrAMlb)" class="yfb2pac1x"/></g><path fill="url(#iDvp61c)" class="yfb2pac1x"/><g filter="url(#ikYBule)"><path class="dyuw2qbvm"/><path fill="url(#i0fii8l)" class="fl8jdgkvu"/><path fill="url(#i2xtQ7c)" class="fl8jdgkvu"/><path fill="url(#iQbtvjb)" class="fl8jdgkvu"/></g><g filter="url(#iSf5QGb)"><circle fill="url(#in03t1b)" class="x5prydbjk"/><circle fill="url(#iHjr1Ec)" class="x5prydbjk"/></g><path fill="url(#ixR1aZd)" class="pwfarzu9b"/><path fill="url(#i8UoQre)" class="nkuar27lq"/><g filter="url(#icJ4JSb)"><path fill="url(#iK4iqGd)" class="gzuvq7bad"/><path fill="url(#isl1Alc)" class="gzuvq7bad"/></g><path fill="url(#imU3m1b)" class="gzuvq7bad"/><path fill="url(#irOsYPb)" class="gzuvq7bad"/><path fill="url(#i4sIhmb)" class="gzuvq7bad"/><path fill="url(#iYpO0BT)" class="gzuvq7bad"/><path fill="url(#iteSMCd)" class="gzuvq7bad"/><path fill="url(#i12XGTc)" class="gzuvq7bad"/><path fill="url(#ijjkcuX)" class="gzuvq7bad"/><g filter="url(#ipAkxOb)"><path class="c-xthiokf"/></g><g filter="url(#iLP6pqd)"><path class="tmt1a2omf"/><path fill="url(#in90mUd)" class="f1_tjnbfv"/><path fill="url(#iImal6E)" class="f1_tjnbfv"/><path fill="url(#iYXxorb)" class="f1_tjnbfv"/><path fill="url(#ib99bxd)" class="f1_tjnbfv"/></g><g filter="url(#ixe6lgd)"><path fill="url(#iGJVCDe)" class="bzy2pib3s"/></g><g filter="url(#ik4bcuS)"><path stroke="url(#iFJEymc)" class="g0q6wacvl"/></g><path fill="url(#izlIgJd)" class="u300poo0p"/><g filter="url(#iQCg20d)"><path fill="url(#iUj8Mob)" class="wic4i3b4m"/><path fill="url(#iH0uBwb)" class="wic4i3b4m"/><path fill="url(#iLqrYlE)" class="wic4i3b4m"/><path fill="url(#iX9AqCd)" class="wic4i3b4m"/><path fill="url(#ilWC88c)" class="wic4i3b4m"/></g><g filter="url(#iU5n9Cd)"><path class="s59lmkbrq"/></g><g filter="url(#imCljAe)"><path class="u6na3hb_j"/></g><g filter="url(#ihGX0ae)"><path class="u7lzn_53o"/><path fill="url(#iTN7ptd)" class="pvfrm704v"/><path fill="url(#iC7Q46J)" class="pvfrm704v"/></g><g filter="url(#iquOlCY)"><path class="chb67dowd"/><path fill="url(#iX7MAYc)" class="dewp-cn2r"/><path fill="url(#iFDTIFB)" class="dewp-cn2r"/></g><path class="iehod0pne"/><path fill="url(#i9tm8py)" class="c5npqxb0h"/><path class="n_y8m0brh"/><g filter="url(#irdE9Ud)"><path class="ja3rhnehj"/><path fill="url(#i4LUGNb)" class="tebcbubsa"/></g><g filter="url(#iRWNX6b)"><path fill="url(#i0O7WFb)" class="hyms7tb1m"/></g><path class="rpwq7iblw"/><path fill="url(#iFhIYvA)" class="q1_ob5b4p"/><path class="qfzp84bkx"/><g filter="url(#iDqbc0c)"><path fill="url(#iw8wwhe)" class="m6kzi4bml"/></g><g filter="url(#ixXri2d)"><ellipse transform="rotate(-27.914 13.559 9.923)" class="orotltb9o"/><ellipse fill="url(#ihDOOAc)" transform="rotate(-27.914 13.559 9.923)" class="vca9s_gbm"/></g><path fill="url(#ilrADHe)" class="m_ozg3bfx"/><path fill="url(#iMAArUb)" class="m_ozg3bfx"/><path fill="url(#iv3cZYc)" class="m_ozg3bfx"/><path fill="url(#iQGZeLd)" class="m_ozg3bfx"/><path fill="url(#i0FCdEb)" class="mvdwa00qm"/><path fill="url(#iVXMofd)" class="mvdwa00qm"/><g filter="url(#iWO38Id)"><path fill="url(#iZnIIPe)" class="ur4x_-b4s"/></g><g filter="url(#inpnF3c)"><path fill="url(#iNu5lIb)" class="vulmhvb9q"/></g><g filter="url(#idViIwe)"><path class="ksbbm39ix"/></g><g filter="url(#i3CFkfc)"><path class="qglif0bug"/></g><g filter="url(#iJJhPzw)"><path class="k-ss30gvu"/></g><defs><radialGradient id="iDFerFe" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.315)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="i0bnV8d" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.77 10.813)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="iKSChfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.226)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iP7xtVK" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.242 2.61)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iKXZx0b" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.127)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="iSGtb3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.383)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="iEQBJ3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.539)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="iEjPYgX" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.506)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iLbvW7l" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.349 13.025)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="ikgV5Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.104 8.356)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="iuTRW6b" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.648)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="iCIUKvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.742)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iv7Upid" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.382)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="imi6qCe" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.075 11.856)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="iKiHcbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.263)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="i6QxIpL" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.322)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="iZVvX9d" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.659 20.617)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iQWVlgf" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.875 16.043)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="i1xsAGY" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.493 14.54)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="igO2Lpb" cx="0" cy="0" r="1" gradientTransform="rotate(83.713 -1.766 17.012)scale(.92745 3.60872)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="mftf-9obd"/><stop offset="1" class="dluxmqbhw"/></radialGradient><radialGradient id="iFAZiTi" cx="0" cy="0" r="1" gradientTransform="matrix(.55469 -.25781 .4579 .98516 14.189 17.607)" gradientUnits="userSpaceOnUse"><stop offset=".44" class="ukg732r2g"/><stop offset="1" class="zmqz16bgv"/></radialGradient><radialGradient id="i3wY97d" cx="0" cy="0" r="1" gradientTransform="rotate(-154.262 11.033 6.956)scale(.82759 1.88786)" gradientUnits="userSpaceOnUse"><stop class="wu3upgb0d"/><stop offset="1" class="m-_zxbjbn"/></radialGradient><radialGradient id="iHrAMlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.73)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iDvp61c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.105)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="i2xtQ7c" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.438 6.855)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="iQbtvjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.96)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="in03t1b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.375 12.583)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iHjr1Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="ixR1aZd" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.848 20.861)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="i8UoQre" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 9.956 12.366)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iK4iqGd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5843 3.28167 -4.12399 -5.76096 18.82 10.934)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="w56j_m4bj"/></radialGradient><radialGradient id="isl1Alc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.54 8.177)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="irOsYPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.27297 7.3692 0 15.994 17.325)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="qpjw51bqc"/><stop offset=".432" class="kwusyxbfn"/><stop offset="1" class="rh-6sjsrx"/></radialGradient><radialGradient id="i4sIhmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.46 9.622)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iYpO0BT" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.707 -2.047)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iteSMCd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.445 11.923)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="i12XGTc" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.22 8.202)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="ijjkcuX" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.129 13.822)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iImal6E" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.479 12.295)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="ib99bxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.595 11.726)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="izlIgJd" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 15.521 14.558)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iH0uBwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.783 8.042)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iLqrYlE" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.33 -6.245)scale(2.51513 4.45632)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iX9AqCd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.119 3.076)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="ilWC88c" cx="0" cy="0" r="1" gradientTransform="matrix(.67168 1.19822 -2.77451 1.5553 15.107 1.484)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iTN7ptd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.266 3.743)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iC7Q46J" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.263 -5.756)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iX7MAYc" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90406 18.646 7.557)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iFDTIFB" cx="0" cy="0" r="1" gradientTransform="matrix(3.24822 .37966 -.15896 1.35997 17.76 6.08)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i9tm8py" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.194 10.018)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i4LUGNb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.966 10.103)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFhIYvA" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.83 10.019)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ihDOOAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.544 10.237)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMAArUb" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.63 10.033)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iv3cZYc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.99 10.577)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iQGZeLd" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.105 10.75)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iVXMofd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.097 10.674)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iZnIIPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.097 10.675)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="iugGZ3V" width="4.081" height="11.683" x="5.07" y="18.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/></filter><filter id="iA3YdUd" width="5.909" height="14.117" x="12.858" y="15.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/></filter><filter id="inGMnAc" width="7.13" height="5.229" x="12.285" y="16.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".3"/></filter><filter id="i0Dkjqc" width="7.239" height="14.645" x="9.195" y="15.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".5"/></filter><filter id="imMCbJb" width="5.917" height="14.31" x="10.326" y="15.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3326" result="effect2_innerShadow_4002_3326"/></filter><filter id="iScKE1c" width="6.504" height="14.261" x="15.345" y="15.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3326" result="effect2_innerShadow_4002_3326"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3326" result="effect3_innerShadow_4002_3326"/></filter><filter id="i5T9Yvd" width="2" height="2" x="14.731" y="24.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".25"/></filter><filter id="ic7fv9c" width="2" height="2" x="14.731" y="21.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".25"/></filter><filter id="iEgXFzc" width="1.05" height="1.05" x="15.504" y="25.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/></filter><filter id="iAEH77b" width="1.05" height="1.05" x="15.504" y="22.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/></filter><filter id="iJLLfwG" width="2.465" height="2.95" x="16.029" y="17.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3326" result="effect2_innerShadow_4002_3326"/></filter><filter id="ikYBule" width="2.365" height="2.9" x="13.731" y="17.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/></filter><filter id="iSf5QGb" width="1.717" height="1.717" x="15.204" y="17.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/></filter><filter id="icJ4JSb" width="11.22" height="12.542" x="10.949" y="4.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3326" result="effect2_innerShadow_4002_3326"/></filter><filter id="ipAkxOb" width="3.747" height="4.9" x="13.997" y="9.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".5"/></filter><filter id="iLP6pqd" width="2.277" height="3.3" x="14.874" y="9.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".1"/></filter><filter id="ixe6lgd" width="2.277" height="3.3" x="14.874" y="9.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".1"/></filter><filter id="ik4bcuS" width="3.718" height="1.573" x="14.153" y="13.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".05"/></filter><filter id="iQCg20d" width="12.873" height="8.356" x="9.576" y="1.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3326" result="effect2_innerShadow_4002_3326"/></filter><filter id="iU5n9Cd" width="2.339" height="1.19" x="17.602" y="7.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/></filter><filter id="imCljAe" width="2.339" height="1.176" x="12.345" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/></filter><filter id="ihGX0ae" width="6.584" height="5.992" x="9.931" y="2.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3326"/><feGaussianBlur result="effect2_foregroundBlur_4002_3326" stdDeviation=".125"/></filter><filter id="iquOlCY" width="6.319" height="5.711" x="15.853" y="3.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".125"/></filter><filter id="irdE9Ud" width=".787" height=".696" x="17.46" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".05"/></filter><filter id="iRWNX6b" width=".891" height=".913" x="18.3" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".1"/></filter><filter id="iDqbc0c" width=".986" height="1.04" x="13.857" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".1"/></filter><filter id="ixXri2d" width=".913" height=".705" x="13.102" y="9.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".05"/></filter><filter id="iWO38Id" width="1.329" height="2.379" x="9.931" y="9.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".125"/></filter><filter id="inpnF3c" width="1.947" height="2.903" x="20.455" y="9.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".25"/></filter><filter id="idViIwe" width="2.405" height="1.16" x="12.264" y="7.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".125"/></filter><filter id="i3CFkfc" width="2.405" height="1.16" x="17.543" y="7.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".125"/></filter><filter id="iJJhPzw" width="5.266" height="3.005" x="16.892" y="3.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3326" stdDeviation=".375"/></filter><linearGradient id="iOzabcD" x1="23.131" x2="22.971" y1="29.905" y2="29.905" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="i92qmGe" x1="8.858" x2="9.061" y1="29.905" y2="29.905" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iVQ1hjc" x1="9.19" x2="7.596" y1="29.913" y2="29.913" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="ivWFWhb" x1="14.705" x2="13.268" y1="19.976" y2="16.851" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="iRSaCgd" x1="15.518" x2="15.209" y1="20.054" y2="19.937" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="i5AU1ke" x1="16.799" x2="18.471" y1="19.992" y2="17.117" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="iqxFvob" x1="16.486" x2="16.713" y1="19.793" y2="19.703" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="iWg0yye" x1="12.815" x2="12.815" y1="16.773" y2="29.418" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="iRlk2ke" x1="17.033" x2="14.649" y1="18.382" y2="17.814" gradientUnits="userSpaceOnUse"><stop class="m38zv9bxu"/><stop offset="1" class="w-42kpbxb"/></linearGradient><linearGradient id="i0fii8l" x1="15.205" x2="14.838" y1="19.429" y2="18.976" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="imU3m1b" x1="21.169" x2="18.64" y1="12.62" y2="12.62" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="in90mUd" x1="16.951" x2="16.012" y1="11.56" y2="11.644" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iYXxorb" x1="16.012" x2="16.012" y1="12.749" y2="12.284" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iGJVCDe" x1="16.012" x2="16.012" y1="9.717" y2="11.053" gradientUnits="userSpaceOnUse"><stop class="yhv8eupnj"/><stop offset="1" class="opak_bkah"/></linearGradient><linearGradient id="iFJEymc" x1="14.81" x2="15.129" y1="14.319" y2="13.485" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iUj8Mob" x1="22.864" x2="11.252" y1="5.272" y2="5.272" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="i0O7WFb" x1="18.972" x2="18.659" y1="10.072" y2="10.265" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iw8wwhe" x1="14.574" x2="14.26" y1="10.072" y2="10.265" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilrADHe" x1="22.449" x2="21.242" y1="10.099" y2="12.275" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="i0FCdEb" x1="10.163" x2="11.621" y1="10.803" y2="10.676" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iNu5lIb" x1="21.429" x2="21.429" y1="9.717" y2="11.621" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-tuxedo-medium-dark" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bzy2pib3s {
  d: path("m15.63 10.023l-.531 1.838c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c-xthiokf {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.611 10.416l-.59 1.838c-.102.378.14.756.484.756h.731c.343 0 .586-.384.485-.756l-.495-1.838c-.106-.408-.504-.408-.615 0");
}

.c5npqxb0h {
  d: path("M18.196 9.542a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
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

.ceclfgb0n {
  d: path("M11.242 18.34c-.03-1.011.55-1.42.819-1.502l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.015c.047.082-.05.176-.132.12c-2.75-1.881-4.776-3.354-5.094-8.18a.19.19 0 0 1 .174-.198c.297-.02.56-.044.747-.061a.19.19 0 0 0 .171-.191c-.01-.53-.02-1.532-.046-2.431");
}

.chb67dowd {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.225 8.586l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.672-1.706 1.651-1.488c.94.209 2.004.558 2.815 1.088c1.745 1.137 1.531 3.12.613 4.085");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
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

.dewp-cn2r {
  d: path("m21.225 8.586l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.672-1.706 1.651-1.488c.94.209 2.004.558 2.815 1.088c1.745 1.137 1.531 3.12.613 4.085");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dluxmqbhw {
  stop-color: var(--svg-color--663247, #663247);
  stop-opacity: 0;
}

.dr-k41b2k {
  cx: 15.731px;
  cy: 25.848px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dyuw2qbvm {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.475l1.813 1.25l-1.795 1.26a.246.246 0 0 1-.389-.188c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.178");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
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

.f1_tjnbfv {
  d: path("m15.63 10.22l-.531 1.838c-.109.379.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
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

.g0q6wacvl {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.661 13.436a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.001c-.39.203-.85.32-1.35.32a2.9 2.9 0 0 1-1.352-.32Z");
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.gzuvq7bad {
  d: path("M11.187 13.7a3.916 3.916 0 0 0 3.886 3.405h1.886a3.916 3.916 0 0 0 3.886-3.405c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4a2.42 2.42 0 0 1-2.212-1.443a.66.66 0 0 0-.615-.418H14.29c-1.845 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hlyur2f6y {
  d: path("M14.41 20.277c-1.185-1.235-1.403-3.047-1.367-3.871h2.969l.035 2.222l-.773 1.52c-.148.308-.608.394-.863.129");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hyms7tb1m {
  d: path("M18.991 10.316a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iehod0pne {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.403 9.27c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.371-1.127");
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.ja3rhnehj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.13 9.73c.065.085-.068.189-.22.302c-.15.113-.263.192-.326.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jockr5brf {
  d: path("M23.099 18.23a10.68 10.68 0 0 1 3.831 8.18v3.496H23.1z");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k-ss30gvu {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.205 5.274h-2.08a.483.483 0 1 1 .076-.96c.54.085 1.257.205 1.737.324c1.086.27 1.386.798 1.47 1.175a1.51 1.51 0 0 0-1.203-.539");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.k8ix0jbxx {
  d: path("M8.901 18.23a10.68 10.68 0 0 0-3.831 8.18v3.496H8.9z");
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.ksbbm39ix {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.64 8.126c.256-.185.897-.51 1.654-.382");
}

.kwusyxbfn {
  stop-color: var(--svg-color--79455b, #79455B);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m_ozg3bfx {
  d: path("M20.934 12.275q.1-1.596.185-3.191a1.61 1.61 0 0 1-.185 3.191");
}

.m-_zxbjbn {
  stop-color: var(--svg-color--75514f, #75514F);
  stop-opacity: 0;
}

.m38zv9bxu {
  stop-color: var(--svg-color--6f4650, #6F4650);
}

.m6kzi4bml {
  d: path("M14.644 10.329c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mftf-9obd {
  stop-color: var(--svg-color--663247, #663247);
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mj9a-09qg {
  d: path("M18.767 16.057a10.3 10.3 0 0 0-2.337-.268h-.86q-1.194.002-2.312.262v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.461 2.57-4.258 2.57-8.433z");
}

.mvdwa00qm {
  d: path("M10.968 9.071a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.n_y8m0brh {
  fill: var(--svg-color--000, #000);
  d: path("M17.685 10.434a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nfw87zbhc {
  d: path("M17.598 20.277c1.186-1.235 1.404-3.047 1.367-3.871h-2.968l-.036 2.222l.774 1.52c.148.308.608.394.863.129");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nkuar27lq {
  d: path("M11.15 12.185a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.341 2.019a4.1 4.1 0 0 1-.346-1.18z");
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.opak_bkah {
  stop-color: var(--svg-color--835955, #835955);
  stop-opacity: 0;
}

.orotltb9o {
  cx: 13.559px;
  cy: 9.923px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pvfrm704v {
  d: path("m16.245 5.319l-.066-.137a.66.66 0 0 0-.616-.418H14.29c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.142-.097.26-.18.332-.253l.1-.105c.349-.37.971-1.031 2.059-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.893v1.485z");
}

.pwfarzu9b {
  d: path("M20.874 12.185a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.019q.257-.546.345-1.18z");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.q1_ob5b4p {
  d: path("M13.828 9.542a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.qfzp84bkx {
  fill: var(--svg-color--000, #000);
  d: path("M14.34 10.434a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.qglif0bug {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.573 8.08c-.257-.185-.897-.51-1.655-.382");
}

.qpjw51bqc {
  stop-color: var(--svg-color--723660, #723660);
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.rh-6sjsrx {
  stop-color: var(--svg-color--79455b, #79455B);
  stop-opacity: 0;
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.rpwq7iblw {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.621 9.27c-.653 0-1.204.45-1.354 1.058a.274.274 0 0 0 .267.341h2.231a.23.23 0 0 0 .228-.272A1.4 1.4 0 0 0 13.62 9.27");
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.s59lmkbrq {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M19.745 7.955a1.85 1.85 0 0 0-.687-.411c-.305-.096-.686-.122-1.213-.057a.277.277 0 1 0 .068.55c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
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

.smrxvvbzr {
  cx: 16.004px;
  cy: 25.575px;
  r: 0.5px;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.svt_7-pew {
  d: path("M11.709 17.543c-.032-1.094.595-1.537.886-1.626l.668-.07v5.815c0 3.873 1.453 6.262 2.712 8.087c.063.091-.047.201-.138.139c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.048.808-.066c.107-.01.188-.1.186-.207c-.011-.574-.023-1.658-.05-2.631");
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tebcbubsa {
  d: path("M18.13 9.73c.065.085-.068.189-.22.302c-.15.113-.263.192-.326.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.ti_8km29h {
  fill: var(--svg-color--9c80b1, #9C80B1);
  d: path("M12.889 16.68c-.037.825.18 2.636 1.367 3.871c.255.266.715.18.863-.129l.73-1.435l.731 1.435a.545.545 0 0 0 .863.13c1.186-1.236 1.404-3.047 1.368-3.872z");
}

.tmt1a2omf {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.63 10.22l-.531 1.838c-.109.379.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.u300poo0p {
  d: path("M16.012 13.831c-.507 0-.984-.12-1.385-.328c-.137-.07-.285.084-.198.209c.335.507.918.846 1.583.846s1.249-.339 1.584-.846c.086-.13-.061-.28-.198-.21a3 3 0 0 1-1.386.329");
}

.u6na3hb_j {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M12.601 7.846a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.002.002a.277.277 0 0 1-.34-.439z");
}

.u7lzn_53o {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.245 5.319l-.066-.137a.66.66 0 0 0-.616-.418H14.29c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.142-.097.26-.18.332-.253l.1-.105c.349-.37.971-1.031 2.059-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.893v1.485z");
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

.ukg732r2g {
  stop-color: var(--svg-color--6c4549, #6C4549);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.ur4x_-b4s {
  d: path("M10.927 9.736a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
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

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vca9s_gbm {
  cx: 13.559px;
  cy: 9.923px;
  rx: 0.39px;
  ry: 0.197px;
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
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

.vscmdxbrb {
  d: path("M8.901 18.23a10.69 10.69 0 0 0-3.831 8.185v3.498H8.9z");
}

.vulmhvb9q {
  d: path("M20.955 11.62q.059-.95.11-1.903a.956.956 0 0 1-.11 1.904");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-42kpbxb {
  stop-color: var(--svg-color--653445, #653445);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w56j_m4bj {
  stop-color: var(--svg-color--734451, #734451);
}

.wic4i3b4m {
  d: path("M20.867 4.292a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.526c-.175.258-.27.564-.27.875v1.188a1.7 1.7 0 0 0-.668-.268l.078-1.607a1.45 1.45 0 0 0-1.378-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.616-.418H14.29c-1.845 0-3.34 1.512-3.34 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.193 0c.282-.118.59-.188.913-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wu3upgb0d {
  stop-color: var(--svg-color--75514f, #75514F);
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x5prydbjk {
  cx: 16.012px;
  cy: 18.695px;
  r: 0.809px;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.yfb2pac1x {
  d: path("m17.892 17.475l-1.813 1.25l1.795 1.26c.159.11.378.006.388-.188c.041-.791.041-1.57.008-2.144a.239.239 0 0 0-.378-.178");
}

.yhv8eupnj {
  stop-color: var(--svg-color--835955, #835955);
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.z8qin0otf {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.316 17.543c.031-1.094-.595-1.537-.887-1.626l-.668-.07v5.815c0 3.873-1.388 6.264-2.648 8.09c-.062.09.047.2.139.138c2.976-2.036 4.851-4.005 5.196-9.228a.203.203 0 0 0-.188-.215c-.321-.02-.607-.048-.809-.066a.204.204 0 0 1-.185-.207c.011-.574.022-1.658.05-2.631");
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zmqz16bgv {
  stop-color: var(--svg-color--6c4549, #6C4549);
  stop-opacity: 0;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

</style>
