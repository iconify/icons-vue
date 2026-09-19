<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQrl49c)"><path fill="url(#iFqpuyc)" class="fjfdrzb7y"/><path fill="url(#iXqA5zb)" class="fjfdrzb7y"/></g><g filter="url(#ix0ebDd)"><path fill="url(#iuxoJ3d)" class="fn9llr-4b"/><path fill="url(#i1y9B7l)" class="fn9llr-4b"/></g><path fill="url(#i4TBK6b)" class="th4v7c7lc"/><path fill="url(#iovfRsd)" class="th4v7c7lc"/><path fill="url(#iS9ZDiI)" class="th4v7c7lc"/><path fill="url(#ipb9C6d)" class="th4v7c7lc"/><path fill="url(#iCVqgAe)" class="th4v7c7lc"/><path fill="url(#iwb90Fe)" class="th4v7c7lc"/><path fill="url(#iYlbYMc)" class="th4v7c7lc"/><path fill="url(#ilLMcAb)" class="th4v7c7lc"/><path fill="url(#iX6SMcd)" class="vipjwwaoi"/><path fill="url(#ielLZkb)" class="vipjwwaoi"/><path fill="url(#iE2SYiX)" class="vipjwwaoi"/><path fill="url(#iS32ave)" class="vipjwwaoi"/><path fill="url(#iLCWise)" class="jd2wixbxg"/><path fill="url(#iGm40Le)" class="jd2wixbxg"/><path fill="url(#iyqCUhb)" class="jd2wixbxg"/><path fill="url(#ibeowCc)" class="jd2wixbxg"/><path fill="url(#iHmM1Fe)" class="f_z9dccjp"/><path fill="url(#iV51ykd)" class="fg2yxxizz"/><path fill="url(#isCaQKY)" class="t3sh78bml"/><g filter="url(#ian3Mde)"><path fill="url(#i5sGDuc)" class="g8c3d4bzs"/><path fill="url(#iDtXXCY)" class="g8c3d4bzs"/><path fill="url(#iMieJUd)" class="g8c3d4bzs"/><path fill="url(#iKEq6hc)" class="g8c3d4bzs"/><path fill="url(#i0CwCve)" class="g8c3d4bzs"/></g><path class="r37i3nnhk"/><path fill="url(#ii3f0eb)" class="y7zv2107g"/><path fill="url(#imDWS3c)" class="y7zv2107g"/><path class="p-hkkqbwc"/><path fill="url(#iNcNc3b)" class="uxo15__pp"/><g filter="url(#ijfySOd)"><path fill="url(#iQmlBWX)" class="pg1pz83lx"/><path fill="url(#irZlZhb)" class="pg1pz83lx"/><path fill="url(#iVaCY7b)" class="pg1pz83lx"/><path fill="url(#iqDO8xd)" class="pg1pz83lx"/><path fill="url(#iPKI3md)" class="pg1pz83lx"/><path fill="url(#iCSSE4c)" class="pg1pz83lx"/></g><g filter="url(#it8IxKb)"><path fill="url(#iEk0t0b)" class="ult9otb7c"/></g><path fill="url(#iZEwBGb)" class="gmo59fbsi"/><path fill="url(#iZVAlYc)" class="gmo59fbsi"/><path fill="url(#iTblmxe)" class="hsuj-b9qt"/><path fill="url(#ieKcP5d)" class="bztm6lbaf"/><path fill="url(#iAPfeUd)" class="bztm6lbaf"/><path fill="url(#iuUNfsy)" class="q6j9fdc3m"/><path fill="url(#iJx5USM)" class="q6j9fdc3m"/><g filter="url(#iYBzBqe)"><circle fill="url(#i1IxFBe)" class="wnzu6gyxf"/><circle fill="url(#imJF0Zc)" class="wnzu6gyxf"/></g><ellipse fill="url(#iJzI5Ge)" transform="rotate(-31.445 16.554 23.508)" class="d9pt9np5n"/><path fill="url(#iiThffb)" class="o5k46v9he"/><path fill="url(#i9qfdGe)" class="zqpmxozeg"/><g filter="url(#ifrph4b)"><path fill="url(#iWy0xCR)" class="i19p2pbvh"/><path fill="url(#iMn7Pio)" class="i19p2pbvh"/></g><path fill="url(#iIApSNc)" class="i19p2pbvh"/><path fill="url(#ibIhE1d)" class="i19p2pbvh"/><path fill="url(#iobh6Lj)" class="i19p2pbvh"/><path fill="url(#i7VIUnd)" class="i19p2pbvh"/><path fill="url(#iqmQMHe)" class="i19p2pbvh"/><path fill="url(#imp1d1C)" class="i19p2pbvh"/><path fill="url(#ixdWUBe)" class="i19p2pbvh"/><path fill="url(#igNDfxb)" class="i19p2pbvh"/><g filter="url(#i7JfpBe)"><path class="uv5b2755x"/></g><g filter="url(#iWqrZzb)"><path class="nivpmdbvs"/><path fill="url(#iXMzc6c)" class="x9vyhnbjt"/><path fill="url(#iOtoZxb)" class="x9vyhnbjt"/><path fill="url(#ibEgZad)" class="x9vyhnbjt"/><path fill="url(#iA4Wamd)" class="x9vyhnbjt"/><path fill="url(#ixiWBrb)" class="x9vyhnbjt"/></g><g filter="url(#iVhyF6n)"><path fill="url(#iKEBvob)" class="u2ky6npan"/><path fill="url(#irWTcmc)" class="u2ky6npan"/><path fill="url(#iCvJwBd)" class="u2ky6npan"/><path fill="url(#i7FjuId)" class="u2ky6npan"/><path fill="url(#ibpW1vd)" class="u2ky6npan"/></g><g filter="url(#iZuFvmc)"><path class="valklh3zf"/><path fill="url(#iKvbZJb)" class="i7xfv9b6j"/><path fill="url(#itJwwHb)" class="i7xfv9b6j"/></g><g filter="url(#iEIF7Ke)"><path class="fgiar0zrd"/><path fill="url(#ikmVQVb)" class="vugs1kb0s"/><path fill="url(#ik3yZ0c)" class="vugs1kb0s"/></g><path fill="url(#iv8XeTc)" class="j8s12zmub"/><path fill="url(#iZPenrb)" class="j8s12zmub"/><path fill="url(#iXmrZIM)" class="j8s12zmub"/><path fill="url(#iWY2Tpd)" class="j8s12zmub"/><path fill="url(#ii2CaHb)" class="rhmmcf2oy"/><path fill="url(#iTcHFze)" class="rhmmcf2oy"/><g filter="url(#i09Wmxc)"><path fill="url(#ioeZOgb)" class="v50-a4bav"/></g><g filter="url(#iOBTJHR)"><path fill="url(#ihiVzFc)" class="mpnyxcbax"/></g><g filter="url(#iaLRJ3c)"><path class="ynvauwbqj"/></g><g filter="url(#i2HeyOd)"><path stroke="url(#ig08k2d)" class="zrw7q7-1s"/></g><path class="ox0674btc"/><g filter="url(#iAYMMqe)"><path class="xjmo8ubir"/></g><g filter="url(#iFnTC3V)"><path fill="url(#iOMXoXb)" class="bqpz40_wg"/><path fill="url(#iqwY84c)" class="bqpz40_wg"/><path fill="url(#iTnpuyd)" class="bqpz40_wg"/></g><path fill="url(#ijDj1xL)" class="bqpz40_wg"/><g filter="url(#ikAjsDc)"><path class="hoyrzxf2o"/></g><g filter="url(#ikkTsvc)"><path class="ujt8c39ck"/></g><defs><radialGradient id="iFqpuyc" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.328 12.649)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iXqA5zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iuxoJ3d" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.26 4.22)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="i1y9B7l" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.119 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="i4TBK6b" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.954)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="iovfRsd" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.4 15.223)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="iS9ZDiI" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.792)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="iCVqgAe" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.338 17.892)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="iwb90Fe" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.267)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="iYlbYMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.642)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iX6SMcd" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.432 25.423)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="ielLZkb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.252 20.267)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="iE2SYiX" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.704)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="iLCWise" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.11)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="iGm40Le" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.173)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="iyqCUhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.86)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="ibeowCc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.454)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="iHmM1Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.07 21.2)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="iV51ykd" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.844)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="isCaQKY" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.844)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iDtXXCY" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.896 58.94)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="iMieJUd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.6)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="iKEq6hc" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.12 15.923)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="i0CwCve" cx="0" cy="0" r="1" gradientTransform="matrix(3.52963 0 0 2.27341 18.523 16.366)" gradientUnits="userSpaceOnUse"><stop class="ge69a97wz"/><stop offset="1" class="jd18rptxw"/></radialGradient><radialGradient id="ii3f0eb" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.579)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="imDWS3c" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.837)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="iNcNc3b" cx="0" cy="0" r="1" gradientTransform="rotate(13.799 -61.433 36.133)scale(.68782 .87718)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="iVaCY7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.358 16.486)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iqDO8xd" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 12.015 7.42)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="iPKI3md" cx="0" cy="0" r="1" gradientTransform="matrix(-7.31239 0 0 -2.83509 14.65 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="sb_6z1bpd"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="iCSSE4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.917)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="iEk0t0b" cx="0" cy="0" r="1" gradientTransform="rotate(160.752 7.093 9.794)scale(3.22747 5.66825)" gradientUnits="userSpaceOnUse"><stop class="tip65z0am"/><stop offset="1" class="ek8xgnb4y"/></radialGradient><radialGradient id="iZEwBGb" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.522 11.535)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="iZVAlYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.776 16.97)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="iTblmxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.72)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="ieKcP5d" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.88 20.941)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iAPfeUd" cx="0" cy="0" r="1" gradientTransform="rotate(-29.297 36.806 -7.1)scale(.99044 .92102)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="iuUNfsy" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.182 16.688)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iJx5USM" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.52344 .50555 .83423 10.26 17.157)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="i1IxFBe" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.085 16.965)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="imJF0Zc" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.485)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="iiThffb" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.943 20.886)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="i9qfdGe" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 10.042 12.294)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iWy0xCR" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.906 10.862)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iMn7Pio" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.604 8.165)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="ibIhE1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.27297 7.3692 0 16.08 17.252)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="iobh6Lj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.545 9.55)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="i7VIUnd" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.714 -2.126)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iqmQMHe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.53 11.85)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="imp1d1C" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.306 8.129)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="ixdWUBe" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.205 13.825)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="igNDfxb" cx="0" cy="0" r="1" gradientTransform="matrix(3.09746 0 0 .75546 16.145 16.58)" gradientUnits="userSpaceOnUse"><stop class="tomv8-b2h"/><stop offset="1" class="d3s-afb9s"/></radialGradient><radialGradient id="iOtoZxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.564 12.223)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iA4Wamd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.68 11.653)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="irWTcmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.869 7.97)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iCvJwBd" cx="0" cy="0" r="1" gradientTransform="matrix(.11404 -2.51254 4.45174 .20206 20.959 9.28)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i7FjuId" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.205 3.004)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="ibpW1vd" cx="0" cy="0" r="1" gradientTransform="matrix(.67168 1.19822 -2.77451 1.5553 15.193 1.411)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iKvbZJb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.352 3.67)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="itJwwHb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.24 -5.87)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ikmVQVb" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90406 18.732 7.485)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="ik3yZ0c" cx="0" cy="0" r="1" gradientTransform="matrix(3.24822 .37966 -.15896 1.35997 17.846 6.008)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iZPenrb" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.716 9.96)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iXmrZIM" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.076 10.504)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iWY2Tpd" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.19 10.677)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iTcHFze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.183 10.6)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="ioeZOgb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.183 10.603)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="ig08k2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57932 2.45245 0 16.245 14.017)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="oq2e0hb8f"/><stop offset="1" class="n52nyrbyw"/></radialGradient><radialGradient id="iOMXoXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.285)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="c7yfkfb_x"/><stop offset=".878" class="ly-mhyl9x"/></radialGradient><radialGradient id="iqwY84c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 13.042)" gradientUnits="userSpaceOnUse"><stop class="cycj4pb5c"/><stop offset="1" class="xkd2ooi4v"/></radialGradient><radialGradient id="iTnpuyd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25001 4.51317 -4.6352 -5.39197 23.432 6.285)" gradientUnits="userSpaceOnUse"><stop class="mbbg-bcay"/><stop offset="1" class="psls5zbwz"/><stop offset="1" class="vyoyvyblw"/></radialGradient><filter id="iQrl49c" width="7.981" height="13.148" x="1.991" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/></filter><filter id="ix0ebDd" width="7.981" height="13.148" x="22.028" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/></filter><filter id="ian3Mde" width="9.078" height="5.683" x="17.916" y="15.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/></filter><filter id="ijfySOd" width="8.928" height="5.533" x="5.258" y="15.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/></filter><filter id="it8IxKb" width="4.194" height="5.942" x="13.971" y="12.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/></filter><filter id="iYBzBqe" width="3.465" height="3.465" x="14.33" y="22.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/></filter><filter id="ifrph4b" width="11.22" height="12.542" x="11.035" y="4.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1001" result="effect2_innerShadow_4002_1001"/></filter><filter id="i7JfpBe" width="3.747" height="4.9" x="14.083" y="9.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1001" stdDeviation=".5"/></filter><filter id="iWqrZzb" width="2.077" height="3.1" x="15.059" y="9.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1001" stdDeviation=".05"/></filter><filter id="iVhyF6n" width="12.873" height="8.357" x="9.662" y="1.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1001" result="effect2_innerShadow_4002_1001"/></filter><filter id="iZuFvmc" width="6.584" height="5.992" x="10.017" y="2.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/><feGaussianBlur result="effect2_foregroundBlur_4002_1001" stdDeviation=".125"/></filter><filter id="iEIF7Ke" width="6.319" height="5.711" x="15.939" y="3.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1001" stdDeviation=".125"/></filter><filter id="i09Wmxc" width="1.329" height="2.379" x="10.017" y="9.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1001" stdDeviation=".125"/></filter><filter id="iOBTJHR" width="1.947" height="2.903" x="20.541" y="9.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1001" stdDeviation=".25"/></filter><filter id="iaLRJ3c" width="5.266" height="3.006" x="16.977" y="3.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1001" stdDeviation=".375"/></filter><filter id="i2HeyOd" width="2.476" height="1.695" x="15.615" y="12.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1001" stdDeviation=".05"/></filter><filter id="iAYMMqe" width="13.891" height="7.06" x="9.087" y="6.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1001" stdDeviation=".375"/></filter><filter id="iFnTC3V" width="15.159" height="7.107" x="8.403" y="6.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.152941 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.333333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1001" result="effect2_innerShadow_4002_1001"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.215686 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1001" result="effect3_innerShadow_4002_1001"/></filter><filter id="ikAjsDc" width="2.192" height="1.627" x="17.223" y="8.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1001" result="effect2_innerShadow_4002_1001"/></filter><filter id="ikkTsvc" width="2.192" height="1.627" x="12.726" y="8.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1001"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1001" result="effect2_innerShadow_4002_1001"/></filter><linearGradient id="ipb9C6d" x1="23.236" x2="22.979" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="ilLMcAb" x1="8.858" x2="8.994" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="iS32ave" x1="23.252" x2="23.486" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="i5sGDuc" x1="25.746" x2="20.292" y1="15.923" y2="20.134" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="iQmlBWX" x1="9.772" x2="9.772" y1="15.917" y2="20.704" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="irZlZhb" x1="9.772" x2="9.772" y1="15.548" y2="17.517" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="iJzI5Ge" x1="16.985" x2="15.947" y1="23.122" y2="24.026" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="iIApSNc" x1="21.255" x2="18.726" y1="12.547" y2="12.547" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iXMzc6c" x1="16.936" x2="16.098" y1="11.537" y2="11.572" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="ibEgZad" x1="16.098" x2="16.098" y1="12.676" y2="12.211" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="ixiWBrb" x1="16.098" x2="16.098" y1="9.971" y2="10.517" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iKEBvob" x1="22.95" x2="11.338" y1="5.199" y2="5.199" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iv8XeTc" x1="22.534" x2="21.328" y1="10.027" y2="12.203" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="ii2CaHb" x1="10.248" x2="11.707" y1="10.73" y2="10.603" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="ihiVzFc" x1="21.514" x2="21.514" y1="9.645" y2="11.548" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="ijDj1xL" x1="10.733" x2="10.979" y1="10.114" y2="9.954" gradientUnits="userSpaceOnUse"><stop offset=".102" class="a5a8_w8qp"/><stop offset=".478" class="ydi8a_bcj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-supervillain-medium-dark" /></template>
<style>
.a--e2mwlv {
  stop-color: var(--svg-color--614b90, #614B90);
}

.a-lmuhb3j {
  stop-color: var(--svg-color--7560a8, #7560A8);
}

.a5a8_w8qp {
  stop-color: var(--svg-color--5e5158, #5E5158);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.av5bbdb4i {
  stop-color: var(--svg-color--ff499d, #FF499D);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b5r8fe9sv {
  stop-color: var(--svg-color--735ca8, #735CA8);
}

.bfw_o9sgk {
  stop-color: var(--svg-color--8977bc, #8977BC);
  stop-opacity: 0;
}

.bkplcs5-b {
  stop-color: var(--svg-color--615181, #615181);
  stop-opacity: 0;
}

.bozoj1btu {
  stop-color: var(--svg-color--e7547f, #E7547F);
  stop-opacity: 0;
}

.bqpz40_wg {
  d: path("m8.576 6.872l3.932 5.84a.75.75 0 0 0 1.185.074l1.761-2.012a.5.5 0 0 0 .104-.185c.098-.292.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.185l1.761 2.012a.75.75 0 0 0 1.185-.073l3.932-5.841c.212-.313-.069-.68-.43-.566L17.2 8.14a.6.6 0 0 0-.338.304c-.216.415-.578.625-.833.631c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.305L9.006 6.306c-.361-.114-.642.253-.43.566");
}

.bztm6lbaf {
  d: path("M7.987 16.95c0 .211.237.3.53.3c.292 0 .529-.112.529-.3a.53.53 0 0 0-1.06 0");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c50kycc4s {
  stop-color: var(--svg-color--ff5292, #FF5292);
  stop-opacity: 0;
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c7yfkfb_x {
  stop-color: var(--svg-color--453753, #453753);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbuctgb-f {
  stop-color: var(--svg-color--dd225e, #DD225E);
  stop-opacity: 0;
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cgymddbwl {
  stop-color: var(--svg-color--3f2563, #3F2563);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ctoai6naw {
  stop-color: var(--svg-color--f93362, #F93362);
}

.cvb6_wfpd {
  stop-color: var(--svg-color--443063, #443063);
}

.cx3r1wb0p {
  stop-color: var(--svg-color--8b74c8, #8B74C8);
}

.cycj4pb5c {
  stop-color: var(--svg-color--322f37, #322F37);
}

.d-jm4nrou {
  stop-color: var(--svg-color--7757b7, #7757B7);
  stop-opacity: 0;
}

.d3s-afb9s {
  stop-color: var(--svg-color--724d51, #724D51);
  stop-opacity: 0;
}

.d9pt9np5n {
  cx: 16.554px;
  cy: 23.508px;
  rx: 0.552px;
  ry: 0.695px;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dkr4vta7s {
  stop-color: var(--svg-color--8977bc, #8977BC);
}

.do8d1irdg {
  stop-color: var(--svg-color--e1658e, #E1658E);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e1q0bl71g {
  stop-color: var(--svg-color--5f4d85, #5F4D85);
  stop-opacity: 0;
}

.e33ikws-z {
  stop-color: var(--svg-color--ff4574, #FF4574);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.e9rx7xb_x {
  stop-color: var(--svg-color--967bc2, #967BC2);
}

.ecn2fkbpq {
  stop-color: var(--svg-color--79659c, #79659C);
  stop-opacity: 0;
}

.ek8xgnb4y {
  stop-color: var(--svg-color--453363, #453363);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f_z9dccjp {
  d: path("m15.575 21.315l-2.98-4.595h6.946l-2.958 4.594a.6.6 0 0 1-1.008.001");
}

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f9nu08mzt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fd6px-b3x {
  stop-color: var(--svg-color--593f75, #593F75);
}

.fdilk9b4n {
  stop-color: var(--svg-color--977fd1, #977FD1);
}

.fg2yxxizz {
  d: path("M23.083 15.964c0 .222-.249.316-.556.316c-.306 0-.555-.12-.555-.316a.555.555 0 1 1 1.11 0");
}

.fgiar0zrd {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.31 8.513l-.028-.631c-.011-.764-.642-1.394-1.406-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.367c-.256-.97.672-1.707 1.65-1.489c.94.21 2.005.559 2.816 1.088c1.744 1.138 1.531 3.12.613 4.085");
}

.fjfdrzb7y {
  d: path("M1.99 29.985h3.532l4.25-8.75l-3.648-4.398C2.71 21.274 1.99 27.22 1.99 29.985");
}

.fn9llr-4b {
  d: path("M30.01 29.985h-3.532l-4.25-8.75l3.648-4.398c3.414 4.437 4.133 10.383 4.133 13.148");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fypjwijgc {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
}

.g2wrz_okq {
  stop-color: var(--svg-color--bb4566, #BB4566);
}

.g8c3d4bzs {
  d: path("M24.635 19.919c-.75 1.082-1.855 1.976-4.008 1.05c-1.836-.788-2.71-3.268-2.71-5.046l8.202.023c.653 0 .752.442.492.856a393 393 0 0 1-1.976 3.117");
}

.ge69a97wz {
  stop-color: var(--svg-color--961241, #961241);
}

.gmo59fbsi {
  d: path("M22.037 16.958c0 .292-.237.367-.53.367c-.291 0-.528-.075-.528-.367a.53.53 0 0 1 1.058 0");
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hoyrzxf2o {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m19.064 8.778l-1.608.593c-.154.057-.235.23-.147.367c.22.343.656.692 1.345.49c.65-.192.792-.815.755-1.257c-.014-.167-.188-.25-.345-.193");
}

.hsuj-b9qt {
  d: path("M24.115 16.958c0 .21-.237.3-.529.3s-.53-.113-.53-.3a.53.53 0 1 1 1.06 0");
}

.i19p2pbvh {
  d: path("M11.273 13.627a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.i3hug6b7s {
  stop-color: var(--svg-color--655586, #655586);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i7xfv9b6j {
  d: path("m16.33 5.246l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38v.274c-.34-.258-.768-.804-.768-1.687c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.012.806.42.806.893v1.485z");
}

.ib49rus2q {
  stop-color: var(--svg-color--72599f, #72599F);
  stop-opacity: 0;
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ie12c-fkv {
  stop-color: var(--svg-color--ee205c, #EE205C);
  stop-opacity: 0;
}

.iek0mvbvg {
  stop-color: var(--svg-color--563680, #563680);
}

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.j8s12zmub {
  d: path("M21.02 12.203q.101-1.595.184-3.192a1.61 1.61 0 0 1-.184 3.192");
}

.jd18rptxw {
  stop-color: var(--svg-color--d31c55, #D31C55);
  stop-opacity: 0;
}

.jd2wixbxg {
  d: path("M8.861 18.142v11.843H4.588c.205-3.069.605-5.613 1.406-7.563c.772-1.881 1.77-3.268 2.867-4.28");
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kejp2n55e {
  stop-color: var(--svg-color--79659c, #79659C);
}

.klsvjl5ds {
  stop-color: var(--svg-color--7056ae, #7056AE);
}

.kr4wgsbgo {
  stop-color: var(--svg-color--533179, #533179);
}

.ksp1sznci {
  stop-color: var(--svg-color--6d55a5, #6D55A5);
  stop-opacity: 0;
}

.l1led_brw {
  stop-color: var(--svg-color--df1d5a, #DF1D5A);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.ly-mhyl9x {
  stop-color: var(--svg-color--4a474e, #4A474E);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m48igd19d {
  stop-color: var(--svg-color--735aa1, #735AA1);
}

.m9hq76bya {
  stop-color: var(--svg-color--64468e, #64468E);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbbg-bcay {
  stop-color: var(--svg-color--625570, #625570);
}

.mpnyxcbax {
  d: path("M21.04 11.548q.06-.951.111-1.903a.956.956 0 0 1-.11 1.903");
}

.mxm28cb7d {
  stop-color: var(--svg-color--735784, #735784);
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n1_6kac4r {
  stop-color: var(--svg-color--745b84, #745B84);
}

.n52nyrbyw {
  stop-color: var(--svg-color--906b6a, #906B6A);
  stop-opacity: 0;
}

.n5x1trblw {
  stop-color: var(--svg-color--73629d, #73629D);
}

.n6ixpp1jb {
  stop-color: var(--svg-color--7da646, #7DA646);
}

.n7j357b5a {
  stop-color: var(--svg-color--230f39, #230F39);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nivpmdbvs {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.716 10.147l-.532 1.839c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.o5k46v9he {
  d: path("M20.96 12.112c.334-.011.648-.125.904-.309v.931c0 .893-.532 1.689-1.341 2.02c.17-.363.287-.759.346-1.18z");
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.ogttk6b6n {
  stop-color: var(--svg-color--774ca5, #774CA5);
}

.oq2e0hb8f {
  stop-color: var(--svg-color--906b6a, #906B6A);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.ox0674btc {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M17.75 12.648c-.614.807-1.368.893-1.872.924c-.085.006-.12.105-.051.154c.377.27.857.293 1.342.09c.51-.213.733-.703.747-1.123c.003-.091-.11-.118-.165-.045");
}

.p-hkkqbwc {
  fill: var(--svg-color--64417a, #64417A);
  d: path("M6.984 15.956c0 .222.249.316.555.316s.556-.119.556-.316a.555.555 0 0 0-1.11 0");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p63xbfaao {
  stop-color: var(--svg-color--85527f, #85527F);
  stop-opacity: 0;
}

.pg1pz83lx {
  d: path("M7.467 19.913c.75 1.082 1.856 1.976 4.008 1.051c1.836-.789 2.711-3.269 2.711-5.047l-8.203.024c-.652 0-.751.441-.492.855c.646 1.03 1.52 2.406 1.976 3.117");
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.psls5zbwz {
  stop-color: var(--svg-color--625570, #625570);
  stop-opacity: 0;
}

.ptuohkesm {
  stop-color: var(--svg-color--cd2172, #CD2172);
  stop-opacity: 0;
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q6j9fdc3m {
  d: path("M10.065 16.95c0 .293.237.367.53.367c.292 0 .529-.075.529-.367a.53.53 0 0 0-1.059 0");
}

.qaycvn_cp {
  stop-color: var(--svg-color--67416e, #67416E);
}

.qf-zh-bgi {
  stop-color: var(--svg-color--755da2, #755DA2);
  stop-opacity: 0;
}

.qsjdql87s {
  stop-color: var(--svg-color--ae495e, #AE495E);
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.r37i3nnhk {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.956c0 .222.248.316.555.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.rhmmcf2oy {
  d: path("M11.054 8.998a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sb_6z1bpd {
  stop-color: var(--svg-color--761032, #761032);
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

.slx6fqref {
  stop-color: var(--svg-color--e1658e, #E1658E);
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

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t3sh78bml {
  d: path("M25.118 15.964c0 .222-.249.316-.555.316s-.556-.12-.556-.316a.555.555 0 0 1 1.11 0");
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.th4v7c7lc {
  d: path("M4.588 29.985h22.938c-.206-3.069-.606-5.613-1.406-7.563c-2.445-5.955-7.16-6.953-10.063-6.812c-2.904-.141-7.618.857-10.063 6.812c-.8 1.95-1.2 4.494-1.406 7.563");
}

.tip65z0am {
  stop-color: var(--svg-color--6c53a3, #6C53A3);
}

.tomv8-b2h {
  stop-color: var(--svg-color--724d51, #724D51);
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tyoz-v6go {
  stop-color: var(--svg-color--cd2172, #CD2172);
}

.u05m0u9vr {
  stop-color: var(--svg-color--ae495e, #AE495E);
  stop-opacity: 0;
}

.u2ky6npan {
  d: path("M20.953 4.22c.514.176.976.535 1.268 1.05a2.37 2.37 0 0 1-.107 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.75 1.75 0 0 0-.667-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38l.03 1.537a1.7 1.7 0 0 0-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.143-2.446a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.383-1.11a2.325 2.325 0 0 1 2.891-.912a1.5 1.5 0 0 0 1.193 0c.281-.118.589-.187.913-.187c.843 0 1.58.456 1.989 1.131c.307.51.79.88 1.352 1.073");
}

.uc4vypayb {
  stop-color: var(--svg-color--8371ae, #8371AE);
}

.uhjz0cbil {
  stop-color: var(--svg-color--e62f68, #E62F68);
  stop-opacity: 0;
}

.ujt8c39ck {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m13.077 8.778l1.607.593c.154.057.236.23.147.367c-.22.343-.656.692-1.345.49c-.65-.192-.792-.815-.755-1.257c.014-.167.188-.25.346-.193");
}

.ujur1qtze {
  stop-color: var(--svg-color--db2a69, #DB2A69);
}

.ult9otb7c {
  d: path("M13.971 15.075a2.097 2.097 0 0 1 4.195 0v1.547c0 1.371-.94 2.098-2.097 2.098c-1.159 0-2.098-.696-2.098-2.097z");
}

.ungg6q-mb {
  stop-color: var(--svg-color--e7547f, #E7547F);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uq-m7pb0g {
  stop-color: var(--svg-color--573a88, #573A88);
}

.uv5b2755x {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.697 10.343l-.591 1.838c-.101.379.141.757.484.757h.732c.343 0 .585-.384.484-.757l-.494-1.838c-.106-.407-.504-.407-.616 0");
}

.uxo15__pp {
  d: path("M6.984 15.956c0 .222.249.316.555.316s.556-.119.556-.316a.555.555 0 0 0-1.11 0");
}

.v_v98qact {
  stop-color: var(--svg-color--230f39, #230F39);
}

.v50-a4bav {
  d: path("M11.013 9.663a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.valklh3zf {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.33 5.246l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38v.274c-.34-.258-.768-.804-.768-1.687c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.012.806.42.806.893v1.485z");
}

.vat9yt_ey {
  stop-color: var(--svg-color--614290, #614290);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vipjwwaoi {
  d: path("M23.252 18.142v11.843h4.274c-.206-3.069-.606-5.613-1.406-7.563c-.773-1.881-1.771-3.268-2.868-4.28");
}

.vugs1kb0s {
  d: path("m21.31 8.513l-.028-.631c-.011-.764-.642-1.394-1.406-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.367c-.256-.97.672-1.707 1.65-1.489c.94.21 2.005.559 2.816 1.088c1.744 1.138 1.531 3.12.613 4.085");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wnzu6gyxf {
  cx: 16.063px;
  cy: 23.995px;
  r: 1.732px;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.x9vyhnbjt {
  d: path("m15.716 10.147l-.532 1.839c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xjmo8ubir {
  fill: var(--svg-color--67393a, #67393A);
  d: path("m9.897 7.99l3.235 4.807a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.153c.08-.24.253-.576.388-.576c.154 0 .313.336.393.576a.4.4 0 0 0 .085.152l1.45 1.656a.617.617 0 0 0 .975-.06l3.235-4.806c.174-.258-.057-.56-.354-.466l-4.821 1.51a.5.5 0 0 0-.278.25c-.178.342-.476.514-.685.52c-.21-.006-.503-.178-.68-.52a.5.5 0 0 0-.278-.25l-4.821-1.51c-.298-.093-.529.208-.354.466");
}

.xkd2ooi4v {
  stop-color: var(--svg-color--322f37, #322F37);
  stop-opacity: 0;
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xrr4vbcci {
  stop-color: var(--svg-color--7560a8, #7560A8);
  stop-opacity: 0;
}

.y-so25ixd {
  stop-color: var(--svg-color--50387f, #50387F);
}

.y06th9bdt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.y7zv2107g {
  d: path("M9.02 15.956c0 .222.248.316.555.316c.306 0 .555-.119.555-.316a.555.555 0 0 0-1.11 0");
}

.ydi8a_bcj {
  stop-color: var(--svg-color--5e5158, #5E5158);
  stop-opacity: 0;
}

.yhvjw36xj {
  stop-color: var(--svg-color--563079, #563079);
}

.ynvauwbqj {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.29 5.202h-2.08a.483.483 0 1 1 .077-.961c.54.086 1.257.206 1.737.325c1.086.269 1.385.797 1.47 1.174a1.51 1.51 0 0 0-1.203-.538");
}

.yog48s40z {
  stop-color: var(--svg-color--ff5292, #FF5292);
}

.yr3p0jbaj {
  stop-color: var(--svg-color--5d3970, #5D3970);
  stop-opacity: 0;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zblf_actk {
  stop-color: var(--svg-color--372543, #372543);
}

.zhe9zhdzx {
  stop-color: var(--svg-color--7a4c9c, #7A4C9C);
}

.zojxemb8i {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
  stop-opacity: 0;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zqpmxozeg {
  d: path("M11.237 12.112a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.zrw7q7-1s {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.75 12.648c-.614.807-1.368.893-1.872.924c-.085.006-.12.105-.051.154c.377.27.857.293 1.342.09c.51-.213.733-.703.747-1.123c.003-.091-.11-.118-.165-.045Z");
}

.zxe--8tbm {
  stop-color: var(--svg-color--50387f, #50387F);
  stop-opacity: 0;
}

</style>
