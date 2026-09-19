<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ifkA4ZS)"><path fill="url(#iFqpuyc)" class="fjfdrzb7y"/><path fill="url(#iXqA5zb)" class="fjfdrzb7y"/></g><g filter="url(#iuVZ3Ne)"><path fill="url(#iuxoJ3d)" class="fn9llr-4b"/><path fill="url(#i1y9B7l)" class="fn9llr-4b"/></g><path fill="url(#i4TBK6b)" class="th4v7c7lc"/><path fill="url(#iovfRsd)" class="th4v7c7lc"/><path fill="url(#iS9ZDiI)" class="th4v7c7lc"/><path fill="url(#ipb9C6d)" class="th4v7c7lc"/><path fill="url(#iCVqgAe)" class="th4v7c7lc"/><path fill="url(#iwb90Fe)" class="th4v7c7lc"/><path fill="url(#iYlbYMc)" class="th4v7c7lc"/><path fill="url(#ilLMcAb)" class="th4v7c7lc"/><path fill="url(#iX6SMcd)" class="vipjwwaoi"/><path fill="url(#ielLZkb)" class="vipjwwaoi"/><path fill="url(#iE2SYiX)" class="vipjwwaoi"/><path fill="url(#iS32ave)" class="vipjwwaoi"/><path fill="url(#iLCWise)" class="jd2wixbxg"/><path fill="url(#iGm40Le)" class="jd2wixbxg"/><path fill="url(#ibWfH0n)" class="jd2wixbxg"/><path fill="url(#ibeowCc)" class="jd2wixbxg"/><path fill="url(#iHmM1Fe)" class="mx-85jb1t"/><path fill="url(#iTXLUYj)" class="dp8i78b9e"/><path fill="url(#iBbC8ab)" class="rjwlhfb5x"/><g filter="url(#iZj9ddS)"><path fill="url(#iMrv4Jc)" class="irvd0gopv"/><path fill="url(#iz2dHcd)" class="irvd0gopv"/><path fill="url(#iMieJUd)" class="irvd0gopv"/><path fill="url(#iKEq6hc)" class="irvd0gopv"/><path fill="url(#i0CwCve)" class="irvd0gopv"/></g><path class="pbx1a_0-e"/><path fill="url(#inyLdJb)" class="dbez5ccgk"/><path fill="url(#imDWS3c)" class="dbez5ccgk"/><path class="r5lwd_9jp"/><path fill="url(#is5rbYb)" class="uvjko3k9x"/><g filter="url(#il0oWFe)"><path fill="url(#iQmlBWX)" class="pnrkvto3p"/><path fill="url(#irZlZhb)" class="pnrkvto3p"/><path fill="url(#iVaCY7b)" class="pnrkvto3p"/><path fill="url(#iqDO8xd)" class="pnrkvto3p"/><path fill="url(#iPKI3md)" class="pnrkvto3p"/><path fill="url(#iCSSE4c)" class="pnrkvto3p"/></g><g filter="url(#i7fluCe)"><path fill="url(#iEk0t0b)" class="kde87nbgw"/></g><path fill="url(#iZEwBGb)" class="gmo59fbsi"/><path fill="url(#iZVAlYc)" class="gmo59fbsi"/><path fill="url(#iTblmxe)" class="gveh8fb-w"/><path fill="url(#ieKcP5d)" class="p-9et7cei"/><path fill="url(#iAPfeUd)" class="p-9et7cei"/><path fill="url(#idyA52b)" class="q6j9fdc3m"/><path fill="url(#iJx5USM)" class="q6j9fdc3m"/><g filter="url(#iWvNIfb)"><circle fill="url(#i1IxFBe)" class="wnzu6gyxf"/><circle fill="url(#imJF0Zc)" class="wnzu6gyxf"/></g><ellipse fill="url(#iJzI5Ge)" transform="rotate(-31.445 16.554 23.508)" class="d9pt9np5n"/><path fill="url(#i9Jpz0d)" class="air8mybko"/><path fill="url(#iPrEgwE)" class="w_uagbcwh"/><g filter="url(#iJFpCww)"><path fill="url(#iK0P76c)" class="i19p2pbvh"/><path fill="url(#isfW4Fe)" class="i19p2pbvh"/></g><path fill="url(#ivKRceM)" class="i19p2pbvh"/><path fill="url(#i4hSkdD)" class="i19p2pbvh"/><path fill="url(#itWKZpb)" class="i19p2pbvh"/><path fill="url(#iM4uc5b)" class="i19p2pbvh"/><path fill="url(#ir0R1rq)" class="i19p2pbvh"/><path fill="url(#is5P8je)" class="i19p2pbvh"/><path fill="url(#ijT0fnV)" class="i19p2pbvh"/><path fill="url(#iXrqJvb)" class="i19p2pbvh"/><g filter="url(#iUQ2iGC)"><path class="uv5b2755x"/></g><g filter="url(#iGCedIe)"><path class="t_6-lzbcb"/><path fill="url(#iWnQ5ld)" class="x9vyhnbjt"/><path fill="url(#iOdSbwb)" class="x9vyhnbjt"/><path fill="url(#iNrB0mc)" class="x9vyhnbjt"/><path fill="url(#iWXsJZb)" class="x9vyhnbjt"/><path fill="url(#i3B0IDc)" class="x9vyhnbjt"/></g><g filter="url(#iNi7ARb)"><path fill="url(#i0GzVud)" class="oxj_7w1mu"/></g><path fill="url(#i0StEdc)" class="oxj_7w1mu"/><path fill="url(#i5cbwpc)" class="oxj_7w1mu"/><path fill="url(#if65TZW)" class="oxj_7w1mu"/><g filter="url(#iCpGPle)"><path class="qd5un3baz"/><path fill="url(#iv0BD0i)" class="z7f29emce"/><path fill="url(#ioBD1Ne)" class="z7f29emce"/></g><g filter="url(#i0FjzFd)"><path class="a38qh0e1t"/><path fill="url(#iIGjDsv)" class="qwwj495nw"/><path fill="url(#iRNeIPd)" class="qwwj495nw"/><path fill="url(#iFXNn0b)" class="qwwj495nw"/></g><path fill="url(#iejxvDw)" class="ry4jhib8o"/><path fill="url(#iOthwbe)" class="ry4jhib8o"/><path fill="url(#ibWrB5d)" class="ry4jhib8o"/><path fill="url(#iZRFXic)" class="ry4jhib8o"/><path fill="url(#iXIpZGi)" class="h7g3_3bsx"/><path fill="url(#iSnwcqe)" class="h7g3_3bsx"/><g filter="url(#iObxFNQ)"><path fill="url(#i4RWTWn)" class="sehudexbf"/></g><g filter="url(#ixeKyku)"><path fill="url(#iTa6ImL)" class="u-pld8cbv"/></g><g filter="url(#iUBZpud)"><path class="g6lfxtpjy"/></g><g filter="url(#imTVsie)"><path stroke="url(#iiscAud)" class="zrw7q7-1s"/></g><path class="ox0674btc"/><g filter="url(#iomxN8m)"><path class="jsw21wy2s"/></g><g filter="url(#iPb5T1b)"><path fill="url(#iOMXoXb)" class="rnkd2acmn"/><path fill="url(#iqwY84c)" class="rnkd2acmn"/><path fill="url(#iTnpuyd)" class="rnkd2acmn"/></g><path fill="url(#ijDj1xL)" class="rnkd2acmn"/><g filter="url(#iamBjcc)"><path class="l7wu4ybff"/></g><g filter="url(#iR9dnHb)"><path class="tdbpv-bck"/></g><defs><radialGradient id="iFqpuyc" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.328 12.649)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iXqA5zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iuxoJ3d" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.26 4.22)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="i1y9B7l" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.119 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="i4TBK6b" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.954)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="iovfRsd" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.4 15.223)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="iS9ZDiI" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.792)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="iCVqgAe" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.338 17.892)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="iwb90Fe" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.267)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="iYlbYMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.642)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iX6SMcd" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.432 25.423)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="ielLZkb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.252 20.267)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="iE2SYiX" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.704)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="iLCWise" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.11)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="iGm40Le" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.173)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="ibWfH0n" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.861)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="ibeowCc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.454)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="iHmM1Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.07 21.2)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="iTXLUYj" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.845)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iBbC8ab" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.845)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iz2dHcd" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.897 58.94)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="iMieJUd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.6)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="iKEq6hc" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.12 15.923)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="i0CwCve" cx="0" cy="0" r="1" gradientTransform="matrix(3.52963 0 0 2.27341 18.523 16.366)" gradientUnits="userSpaceOnUse"><stop class="ge69a97wz"/><stop offset="1" class="jd18rptxw"/></radialGradient><radialGradient id="inyLdJb" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.58)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="imDWS3c" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.837)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="is5rbYb" cx="0" cy="0" r="1" gradientTransform="rotate(13.799 -61.434 36.133)scale(.68782 .87718)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="iVaCY7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.358 16.486)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iqDO8xd" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 12.015 7.42)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="iPKI3md" cx="0" cy="0" r="1" gradientTransform="matrix(-7.31239 0 0 -2.83509 14.65 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="sb_6z1bpd"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="iCSSE4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.917)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="iEk0t0b" cx="0" cy="0" r="1" gradientTransform="rotate(160.752 7.093 9.794)scale(3.22747 5.66825)" gradientUnits="userSpaceOnUse"><stop class="tip65z0am"/><stop offset="1" class="ek8xgnb4y"/></radialGradient><radialGradient id="iZEwBGb" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.522 11.535)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="iZVAlYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.776 16.97)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="iTblmxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.72)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="ieKcP5d" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.88 20.941)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iAPfeUd" cx="0" cy="0" r="1" gradientTransform="rotate(-29.297 36.806 -7.1)scale(.99044 .92102)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="idyA52b" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.182 16.689)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iJx5USM" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.52344 .50555 .83423 10.26 17.157)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="i1IxFBe" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.085 16.965)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="imJF0Zc" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.485)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="i9Jpz0d" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.943 20.886)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iPrEgwE" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 10.042 12.294)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iK0P76c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 18.906 10.862)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="isfW4Fe" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.604 8.165)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="i4hSkdD" cx="0" cy="0" r="1" gradientTransform="matrix(-.13678 12.53065 -10.37688 -.11327 16.794 4.841)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="omsktlboh"/><stop offset=".99" class="p8udvg95v"/></radialGradient><radialGradient id="itWKZpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.545 9.55)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iM4uc5b" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.714 -2.126)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="ir0R1rq" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49598 .5363 -1.37 -21.703 19.53 11.85)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="is5P8je" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.306 8.129)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="ijT0fnV" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.205 13.825)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iXrqJvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 13.882 10.367)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iOdSbwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.564 12.223)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iWXsJZb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.68 11.653)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="i0StEdc" cx="0" cy="0" r="1" gradientTransform="matrix(2.7406 -7.14959 10.14519 3.88889 10.39 8.937)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="i5cbwpc" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.46 -4.152)scale(6.72756 9.54634)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="if65TZW" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 11.151 -3.755)scale(2.63838 3.11466)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iv0BD0i" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.351 3.67)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="ioBD1Ne" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.24 -5.87)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iIGjDsv" cx="0" cy="0" r="1" gradientTransform="rotate(-38.837 17.84 -22.44)scale(4.51284 6.99393)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iRNeIPd" cx="0" cy="0" r="1" gradientTransform="matrix(2.95886 -2.64821 4.8482 5.41692 18.731 7.485)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iFXNn0b" cx="0" cy="0" r="1" gradientTransform="matrix(3.22527 .72413 -.30318 1.35036 17.868 5.663)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iOthwbe" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.716 9.96)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="ibWrB5d" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.076 10.504)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iZRFXic" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.19 10.677)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iSnwcqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.183 10.6)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i4RWTWn" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.183 10.603)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iiscAud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57932 2.45245 0 16.245 14.017)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="dieblkbhn"/><stop offset="1" class="j1ry9jcqp"/></radialGradient><radialGradient id="iOMXoXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.285)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="c7yfkfb_x"/><stop offset=".878" class="ly-mhyl9x"/></radialGradient><radialGradient id="iqwY84c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 13.042)" gradientUnits="userSpaceOnUse"><stop class="cycj4pb5c"/><stop offset="1" class="xkd2ooi4v"/></radialGradient><radialGradient id="iTnpuyd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25001 4.51317 -4.6352 -5.39197 23.432 6.285)" gradientUnits="userSpaceOnUse"><stop class="mbbg-bcay"/><stop offset="1" class="psls5zbwz"/><stop offset="1" class="vyoyvyblw"/></radialGradient><filter id="ifkA4ZS" width="7.981" height="13.148" x="1.991" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/></filter><filter id="iuVZ3Ne" width="7.981" height="13.148" x="22.028" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/></filter><filter id="iZj9ddS" width="9.078" height="5.683" x="17.916" y="15.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/></filter><filter id="il0oWFe" width="8.928" height="5.533" x="5.258" y="15.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/></filter><filter id="i7fluCe" width="4.194" height="5.942" x="13.971" y="12.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/></filter><filter id="iWvNIfb" width="3.465" height="3.465" x="14.33" y="22.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/></filter><filter id="iJFpCww" width="11.22" height="12.442" x="11.035" y="4.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1004" result="effect2_innerShadow_4002_1004"/></filter><filter id="iUQ2iGC" width="3.747" height="4.9" x="14.083" y="9.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1004" stdDeviation=".5"/></filter><filter id="iGCedIe" width="2.077" height="3.1" x="15.059" y="9.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1004" stdDeviation=".05"/></filter><filter id="iNi7ARb" width="12.873" height="8.357" x="9.662" y="1.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1004" result="effect2_innerShadow_4002_1004"/></filter><filter id="iCpGPle" width="6.584" height="5.992" x="10.017" y="2.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/><feGaussianBlur result="effect2_foregroundBlur_4002_1004" stdDeviation=".125"/></filter><filter id="i0FjzFd" width="7.112" height="5.986" x="15.939" y="2.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/><feGaussianBlur result="effect2_foregroundBlur_4002_1004" stdDeviation=".125"/></filter><filter id="iObxFNQ" width="1.329" height="2.379" x="10.017" y="9.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1004" stdDeviation=".125"/></filter><filter id="ixeKyku" width="1.806" height="2.758" x="20.648" y="9.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1004" stdDeviation=".25"/></filter><filter id="iUBZpud" width="5.367" height="3.046" x="17.114" y="3.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1004" stdDeviation=".375"/></filter><filter id="imTVsie" width="2.476" height="1.695" x="15.615" y="12.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1004" stdDeviation=".05"/></filter><filter id="iomxN8m" width="13.891" height="7.06" x="9.087" y="6.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1004" stdDeviation=".375"/></filter><filter id="iPb5T1b" width="15.159" height="7.107" x="8.403" y="6.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.152941 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.333333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1004" result="effect2_innerShadow_4002_1004"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.215686 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1004" result="effect3_innerShadow_4002_1004"/></filter><filter id="iamBjcc" width="2.192" height="1.627" x="17.223" y="8.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1004" result="effect2_innerShadow_4002_1004"/></filter><filter id="iR9dnHb" width="2.192" height="1.627" x="12.726" y="8.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.505882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1004"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.886275 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1004" result="effect2_innerShadow_4002_1004"/></filter><linearGradient id="ipb9C6d" x1="23.236" x2="22.979" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="ilLMcAb" x1="8.858" x2="8.994" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="iS32ave" x1="23.252" x2="23.486" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="iMrv4Jc" x1="25.746" x2="20.292" y1="15.923" y2="20.135" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="iQmlBWX" x1="9.772" x2="9.772" y1="15.917" y2="20.704" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="irZlZhb" x1="9.772" x2="9.772" y1="15.548" y2="17.517" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="iJzI5Ge" x1="16.985" x2="15.947" y1="23.122" y2="24.026" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="ivKRceM" x1="21.255" x2="18.726" y1="12.547" y2="12.547" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iWnQ5ld" x1="16.936" x2="16.098" y1="11.537" y2="11.572" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iNrB0mc" x1="16.098" x2="16.098" y1="12.676" y2="12.211" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="i3B0IDc" x1="16.098" x2="16.098" y1="9.971" y2="10.518" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="i0GzVud" x1="22.95" x2="11.338" y1="5.199" y2="5.199" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iejxvDw" x1="22.534" x2="21.328" y1="10.027" y2="12.203" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iXIpZGi" x1="10.248" x2="11.707" y1="10.731" y2="10.603" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iTa6ImL" x1="21.551" x2="21.551" y1="9.718" y2="11.475" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="ijDj1xL" x1="10.733" x2="10.979" y1="10.114" y2="9.954" gradientUnits="userSpaceOnUse"><stop offset=".102" class="a5a8_w8qp"/><stop offset=".478" class="ydi8a_bcj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-supervillain-medium" /></template>
<style>
.a--e2mwlv {
  stop-color: var(--svg-color--614b90, #614B90);
}

.a-lmuhb3j {
  stop-color: var(--svg-color--7560a8, #7560A8);
}

.a38qh0e1t {
  fill: var(--svg-color--563936, #563936);
  d: path("m21.31 8.513l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.367c-.256-.97.67-1.713 1.656-1.522c.973.189 2.082.517 2.902 1.052c1.744 1.138 1.439 3.188.52 4.154");
}

.a5a8_w8qp {
  stop-color: var(--svg-color--5e5158, #5E5158);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.air8mybko {
  d: path("M20.96 12.112c.334-.011.648-.125.904-.309v.931c0 .893-.532 1.69-1.341 2.02a4.1 4.1 0 0 0 .346-1.18z");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.av5bbdb4i {
  stop-color: var(--svg-color--ff499d, #FF499D);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b5r8fe9sv {
  stop-color: var(--svg-color--735ca8, #735CA8);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bfw_o9sgk {
  stop-color: var(--svg-color--8977bc, #8977BC);
  stop-opacity: 0;
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bkplcs5-b {
  stop-color: var(--svg-color--615181, #615181);
  stop-opacity: 0;
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.bozoj1btu {
  stop-color: var(--svg-color--e7547f, #E7547F);
  stop-opacity: 0;
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c50kycc4s {
  stop-color: var(--svg-color--ff5292, #FF5292);
  stop-opacity: 0;
}

.c7yfkfb_x {
  stop-color: var(--svg-color--453753, #453753);
}

.cbuctgb-f {
  stop-color: var(--svg-color--dd225e, #DD225E);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cgymddbwl {
  stop-color: var(--svg-color--3f2563, #3F2563);
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

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d9pt9np5n {
  cx: 16.554px;
  cy: 23.508px;
  rx: 0.552px;
  ry: 0.695px;
}

.dbez5ccgk {
  d: path("M9.02 15.957c0 .22.248.315.555.315c.306 0 .555-.119.555-.315a.555.555 0 0 0-1.11 0");
}

.dieblkbhn {
  stop-color: var(--svg-color--b88e84, #B88E84);
}

.dkr4vta7s {
  stop-color: var(--svg-color--8977bc, #8977BC);
}

.do8d1irdg {
  stop-color: var(--svg-color--e1658e, #E1658E);
}

.dp8i78b9e {
  d: path("M23.083 15.964c0 .222-.249.316-.556.316c-.306 0-.555-.119-.555-.316a.555.555 0 1 1 1.11 0");
}

.e1q0bl71g {
  stop-color: var(--svg-color--5f4d85, #5F4D85);
  stop-opacity: 0;
}

.e33ikws-z {
  stop-color: var(--svg-color--ff4574, #FF4574);
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

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f9nu08mzt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd6px-b3x {
  stop-color: var(--svg-color--593f75, #593F75);
}

.fdilk9b4n {
  stop-color: var(--svg-color--977fd1, #977FD1);
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fjfdrzb7y {
  d: path("M1.99 29.985h3.532l4.25-8.75l-3.648-4.398C2.71 21.274 1.99 27.22 1.99 29.985");
}

.fn9llr-4b {
  d: path("M30.01 29.985h-3.532l-4.25-8.75l3.648-4.398c3.414 4.437 4.133 10.383 4.133 13.148");
}

.ft5dv1b6b {
  fill: none;
}

.fypjwijgc {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g2wrz_okq {
  stop-color: var(--svg-color--bb4566, #BB4566);
}

.g6lfxtpjy {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.497 5.25H18.36a.496.496 0 1 1 .079-.988c.554.089 1.29.212 1.784.334c1.114.276 1.422.819 1.508 1.206a1.55 1.55 0 0 0-1.235-.553");
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.ge69a97wz {
  stop-color: var(--svg-color--961241, #961241);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gmo59fbsi {
  d: path("M22.037 16.958c0 .292-.237.367-.53.367c-.291 0-.528-.075-.528-.367a.53.53 0 0 1 1.058 0");
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gveh8fb-w {
  d: path("M24.115 16.958c0 .211-.237.3-.529.3s-.53-.113-.53-.3a.53.53 0 1 1 1.06 0");
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h7g3_3bsx {
  d: path("M11.054 8.999a1.62 1.62 0 0 0-1.392 1.598c0 .859.673 1.56 1.52 1.606A78 78 0 0 1 11.055 9");
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.i19p2pbvh {
  d: path("M11.273 13.627a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.i3hug6b7s {
  stop-color: var(--svg-color--655586, #655586);
}

.ib49rus2q {
  stop-color: var(--svg-color--72599f, #72599F);
  stop-opacity: 0;
}

.ie12c-fkv {
  stop-color: var(--svg-color--ee205c, #EE205C);
  stop-opacity: 0;
}

.iek0mvbvg {
  stop-color: var(--svg-color--563680, #563680);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.irvd0gopv {
  d: path("M24.635 19.919c-.75 1.082-1.855 1.976-4.008 1.05c-1.836-.788-2.71-3.268-2.71-5.046l8.202.023c.653 0 .752.442.492.856a376 376 0 0 1-1.976 3.117");
}

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.j1ry9jcqp {
  stop-color: var(--svg-color--b88e84, #B88E84);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jd18rptxw {
  stop-color: var(--svg-color--d31c55, #D31C55);
  stop-opacity: 0;
}

.jd2wixbxg {
  d: path("M8.861 18.142v11.843H4.588c.205-3.069.605-5.613 1.406-7.563c.772-1.881 1.77-3.268 2.867-4.28");
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jsw21wy2s {
  fill: var(--svg-color--7a4b51, #7A4B51);
  d: path("m9.897 7.99l3.235 4.807a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.153c.08-.24.253-.576.388-.576c.154 0 .313.336.393.576a.4.4 0 0 0 .085.153l1.45 1.655a.617.617 0 0 0 .975-.06l3.235-4.806c.174-.258-.057-.56-.354-.466l-4.821 1.51a.5.5 0 0 0-.278.25c-.178.342-.476.514-.685.52c-.21-.006-.503-.178-.68-.52a.5.5 0 0 0-.278-.25l-4.821-1.51c-.298-.093-.529.208-.354.466");
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
}

.kde87nbgw {
  d: path("M13.971 15.075a2.097 2.097 0 0 1 4.195 0v1.548c0 1.37-.94 2.097-2.097 2.097c-1.159 0-2.098-.696-2.098-2.097z");
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

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l1led_brw {
  stop-color: var(--svg-color--df1d5a, #DF1D5A);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7wu4ybff {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m19.064 8.778l-1.608.593c-.154.057-.235.23-.147.367c.22.343.656.693 1.345.49c.65-.192.792-.815.755-1.257c-.014-.167-.188-.25-.345-.193");
}

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.ly-mhyl9x {
  stop-color: var(--svg-color--4a474e, #4A474E);
}

.m48igd19d {
  stop-color: var(--svg-color--735aa1, #735AA1);
}

.m9hq76bya {
  stop-color: var(--svg-color--64468e, #64468E);
}

.mbbg-bcay {
  stop-color: var(--svg-color--625570, #625570);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.mx-85jb1t {
  d: path("m15.575 21.316l-2.98-4.596h6.946l-2.958 4.594a.6.6 0 0 1-1.008.002");
}

.mxm28cb7d {
  stop-color: var(--svg-color--735784, #735784);
}

.n1_6kac4r {
  stop-color: var(--svg-color--745b84, #745B84);
}

.n5x1trblw {
  stop-color: var(--svg-color--73629d, #73629D);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n6ixpp1jb {
  stop-color: var(--svg-color--7da646, #7DA646);
}

.n7j357b5a {
  stop-color: var(--svg-color--230f39, #230F39);
  stop-opacity: 0;
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ogttk6b6n {
  stop-color: var(--svg-color--774ca5, #774CA5);
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.omsktlboh {
  stop-color: var(--svg-color--9e6871, #9E6871);
  stop-opacity: 0;
}

.ox0674btc {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M17.75 12.648c-.614.807-1.368.893-1.872.924c-.085.006-.12.105-.051.154c.377.27.857.293 1.342.09c.51-.213.733-.703.747-1.123c.003-.091-.11-.118-.165-.045");
}

.oxj_7w1mu {
  d: path("M20.953 4.22c.514.176.976.535 1.268 1.05a2.37 2.37 0 0 1-.107 2.527c-.175.257-.27.563-.27.874v1.188a1.75 1.75 0 0 0-.667-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38l.03 1.537a1.7 1.7 0 0 0-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.143-2.446a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.383-1.11a2.325 2.325 0 0 1 2.891-.912a1.5 1.5 0 0 0 1.193 0c.281-.118.589-.187.913-.187c.843 0 1.58.456 1.989 1.131c.307.51.79.88 1.352 1.073");
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p-9et7cei {
  d: path("M7.987 16.95c0 .211.237.301.53.301c.292 0 .529-.113.529-.3a.53.53 0 0 0-1.06 0");
}

.p63xbfaao {
  stop-color: var(--svg-color--85527f, #85527F);
  stop-opacity: 0;
}

.p8udvg95v {
  stop-color: var(--svg-color--9c5967, #9C5967);
}

.pbx1a_0-e {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.957c0 .22.248.315.555.315c.306 0 .555-.119.555-.315a.555.555 0 0 0-1.11 0");
}

.pnrkvto3p {
  d: path("M7.467 19.913c.75 1.082 1.856 1.976 4.008 1.051c1.836-.789 2.711-3.269 2.711-5.047l-8.203.024c-.652 0-.751.442-.492.855c.646 1.03 1.52 2.406 1.976 3.117");
}

.psls5zbwz {
  stop-color: var(--svg-color--625570, #625570);
  stop-opacity: 0;
}

.ptuohkesm {
  stop-color: var(--svg-color--cd2172, #CD2172);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q6j9fdc3m {
  d: path("M10.065 16.95c0 .293.237.367.53.367c.292 0 .529-.075.529-.367a.53.53 0 0 0-1.059 0");
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qaycvn_cp {
  stop-color: var(--svg-color--67416e, #67416E);
}

.qd5un3baz {
  fill: var(--svg-color--533634, #533634);
  d: path("m16.33 5.246l-.066-.136a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38v.274c-.34-.258-.768-.804-.768-1.687c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.03 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.012.806.42.806.893v1.485z");
}

.qf-zh-bgi {
  stop-color: var(--svg-color--755da2, #755DA2);
  stop-opacity: 0;
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qsjdql87s {
  stop-color: var(--svg-color--ae495e, #AE495E);
}

.qwwj495nw {
  d: path("m21.31 8.513l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.367c-.256-.97.67-1.713 1.656-1.522c.973.189 2.082.517 2.902 1.052c1.744 1.138 1.439 3.188.52 4.154");
}

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r5lwd_9jp {
  fill: var(--svg-color--64417a, #64417A);
  d: path("M6.984 15.957c0 .22.249.315.555.315s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.rjwlhfb5x {
  d: path("M25.118 15.964c0 .222-.249.316-.555.316s-.556-.119-.556-.316a.555.555 0 0 1 1.11 0");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rnkd2acmn {
  d: path("m8.576 6.872l3.932 5.84a.75.75 0 0 0 1.185.074l1.761-2.012a.5.5 0 0 0 .104-.185c.098-.291.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.185l1.761 2.012a.75.75 0 0 0 1.185-.073l3.932-5.84c.212-.314-.069-.68-.43-.567L17.2 8.14a.6.6 0 0 0-.338.304c-.216.415-.578.625-.833.631c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.305L9.006 6.306c-.361-.113-.642.253-.43.566");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.ry4jhib8o {
  d: path("M21.02 12.203q.101-1.595.184-3.191a1.61 1.61 0 0 1-.184 3.19");
}

.sb_6z1bpd {
  stop-color: var(--svg-color--761032, #761032);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sehudexbf {
  d: path("M11.012 9.664a.956.956 0 0 0 .084 1.879a78 78 0 0 1-.084-1.88");
}

.slx6fqref {
  stop-color: var(--svg-color--e1658e, #E1658E);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t_6-lzbcb {
  fill: var(--svg-color--9c7666, #9C7666);
  d: path("m15.716 10.147l-.532 1.839c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.tdbpv-bck {
  fill: var(--svg-color--92d55c, #92D55C);
  d: path("m13.077 8.778l1.607.593c.154.057.236.23.147.367c-.22.343-.656.693-1.345.49c-.65-.192-.792-.815-.755-1.257c.014-.167.188-.25.346-.193");
}

.th4v7c7lc {
  d: path("M4.588 29.985h22.938c-.206-3.069-.606-5.613-1.406-7.563c-2.445-5.955-7.16-6.953-10.063-6.812c-2.904-.141-7.618.857-10.063 6.812c-.8 1.95-1.2 4.494-1.406 7.563");
}

.tip65z0am {
  stop-color: var(--svg-color--6c53a3, #6C53A3);
}

.tyoz-v6go {
  stop-color: var(--svg-color--cd2172, #CD2172);
}

.u-pld8cbv {
  d: path("M21.148 11.475q.05-.879.095-1.757c.4.054.711.425.711.875c0 .485-.36.878-.806.882");
}

.u05m0u9vr {
  stop-color: var(--svg-color--ae495e, #AE495E);
  stop-opacity: 0;
}

.uc4vypayb {
  stop-color: var(--svg-color--8371ae, #8371AE);
}

.uhjz0cbil {
  stop-color: var(--svg-color--e62f68, #E62F68);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ujur1qtze {
  stop-color: var(--svg-color--db2a69, #DB2A69);
}

.ungg6q-mb {
  stop-color: var(--svg-color--e7547f, #E7547F);
}

.uq-m7pb0g {
  stop-color: var(--svg-color--573a88, #573A88);
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uv5b2755x {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.697 10.343l-.591 1.838c-.101.379.141.757.484.757h.732c.343 0 .585-.384.484-.757l-.494-1.838c-.106-.407-.504-.407-.616 0");
}

.uvjko3k9x {
  d: path("M6.984 15.957c0 .22.249.315.555.315s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v_v98qact {
  stop-color: var(--svg-color--230f39, #230F39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
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

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w_uagbcwh {
  d: path("M11.237 12.112a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wnzu6gyxf {
  cx: 16.063px;
  cy: 23.995px;
  r: 1.732px;
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x9vyhnbjt {
  d: path("m15.716 10.147l-.532 1.839c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xkd2ooi4v {
  stop-color: var(--svg-color--322f37, #322F37);
  stop-opacity: 0;
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xrr4vbcci {
  stop-color: var(--svg-color--7560a8, #7560A8);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y-so25ixd {
  stop-color: var(--svg-color--50387f, #50387F);
}

.y06th9bdt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.ydi8a_bcj {
  stop-color: var(--svg-color--5e5158, #5E5158);
  stop-opacity: 0;
}

.yhvjw36xj {
  stop-color: var(--svg-color--563079, #563079);
}

.yog48s40z {
  stop-color: var(--svg-color--ff5292, #FF5292);
}

.yr3p0jbaj {
  stop-color: var(--svg-color--5d3970, #5D3970);
  stop-opacity: 0;
}

.z7f29emce {
  d: path("m16.33 5.246l-.066-.136a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38v.274c-.34-.258-.768-.804-.768-1.687c0-1.072.782-1.614 1.28-1.96c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.03 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.012.806.42.806.893v1.485z");
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

.zrw7q7-1s {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.75 12.648c-.614.807-1.368.893-1.872.924c-.085.006-.12.105-.051.154c.377.27.857.293 1.342.09c.51-.213.733-.703.747-1.123c.003-.091-.11-.118-.165-.045Z");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zxe--8tbm {
  stop-color: var(--svg-color--50387f, #50387F);
  stop-opacity: 0;
}

</style>
