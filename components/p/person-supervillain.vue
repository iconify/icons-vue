<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4mXLlc)"><path fill="url(#iFqpuyc)" class="fjfdrzb7y"/><path fill="url(#iXqA5zb)" class="fjfdrzb7y"/></g><g filter="url(#iTL3OTc)"><path fill="url(#iuxoJ3d)" class="fn9llr-4b"/><path fill="url(#i1y9B7l)" class="fn9llr-4b"/></g><path fill="url(#i4TBK6b)" class="th4v7c7lc"/><path fill="url(#iovfRsd)" class="th4v7c7lc"/><path fill="url(#iS9ZDiI)" class="th4v7c7lc"/><path fill="url(#ipb9C6d)" class="th4v7c7lc"/><path fill="url(#iCVqgAe)" class="th4v7c7lc"/><path fill="url(#iwb90Fe)" class="th4v7c7lc"/><path fill="url(#iYlbYMc)" class="th4v7c7lc"/><path fill="url(#ilLMcAb)" class="th4v7c7lc"/><path fill="url(#iX6SMcd)" class="vipjwwaoi"/><path fill="url(#ielLZkb)" class="vipjwwaoi"/><path fill="url(#iE2SYiX)" class="vipjwwaoi"/><path fill="url(#iS32ave)" class="vipjwwaoi"/><path fill="url(#iLCWise)" class="jd2wixbxg"/><path fill="url(#iGm40Le)" class="jd2wixbxg"/><path fill="url(#ibWfH0n)" class="jd2wixbxg"/><path fill="url(#ibeowCc)" class="jd2wixbxg"/><path fill="url(#iHmM1Fe)" class="f_z9dccjp"/><path fill="url(#iTXLUYj)" class="fg2yxxizz"/><path fill="url(#iBbC8ab)" class="t3sh78bml"/><g filter="url(#i38wezd)"><path fill="url(#i5sGDuc)" class="irvd0gopv"/><path fill="url(#iDtXXCY)" class="irvd0gopv"/><path fill="url(#iMieJUd)" class="irvd0gopv"/><path fill="url(#iKEq6hc)" class="irvd0gopv"/></g><path class="pbx1a_0-e"/><path fill="url(#inyLdJb)" class="dbez5ccgk"/><path fill="url(#imDWS3c)" class="dbez5ccgk"/><path class="r5lwd_9jp"/><path fill="url(#is5rbYb)" class="uvjko3k9x"/><g filter="url(#iCLTwNe)"><path fill="url(#iQmlBWX)" class="pnrkvto3p"/><path fill="url(#irZlZhb)" class="pnrkvto3p"/><path fill="url(#iVaCY7b)" class="pnrkvto3p"/><path fill="url(#iqDO8xd)" class="pnrkvto3p"/><path fill="url(#iuqiK1d)" class="pnrkvto3p"/><path fill="url(#iCSSE4c)" class="pnrkvto3p"/></g><g filter="url(#isTibMg)"><path fill="url(#i4xyObx)" class="ult9otb7c"/></g><path fill="url(#iZEwBGb)" class="gmo59fbsi"/><path fill="url(#iZVAlYc)" class="gmo59fbsi"/><path fill="url(#iTblmxe)" class="hsuj-b9qt"/><path fill="url(#ieKcP5d)" class="t_0girb4l"/><path fill="url(#iAPfeUd)" class="t_0girb4l"/><path fill="url(#iuUNfsy)" class="lmv51mb1h"/><path fill="url(#iJx5USM)" class="lmv51mb1h"/><g filter="url(#iYTaBco)"><circle fill="url(#i1IxFBe)" class="wnzu6gyxf"/><circle fill="url(#imJF0Zc)" class="wnzu6gyxf"/></g><ellipse fill="url(#iJzI5Ge)" transform="rotate(-31.445 16.554 23.508)" class="d9pt9np5n"/><path fill="url(#ia5AYhd)" class="apxwuphud"/><path fill="url(#iZG9K8b)" class="apxwuphud"/><path fill="url(#i2DrNKd)" class="sdwnt9exm"/><g filter="url(#i209rhc)"><path fill="url(#iKCfocb)" class="z8xki-b3f"/></g><path fill="url(#iVCmRnb)" class="z8xki-b3f"/><path fill="url(#irRiS4d)" class="z8xki-b3f"/><path fill="url(#ixOhB9J)" class="z8xki-b3f"/><path fill="url(#ifkTpqb)" class="z8xki-b3f"/><g filter="url(#iHAwKZd)"><path class="y5cz88bph"/></g><g filter="url(#iIK5uCc)"><path class="k-a516hzq"/></g><g filter="url(#iLFeRjc)"><path class="hzf8hkb5j"/><path fill="url(#ijqfU6b)" class="xo7sfdbbq"/><path fill="url(#igg8ZNe)" class="xo7sfdbbq"/></g><g filter="url(#ismw7Pb)"><path fill="url(#iswSTLG)" class="olr-q-b8n"/><path fill="url(#iGsx6kU)" class="olr-q-b8n"/><path fill="url(#iT58akb)" class="olr-q-b8n"/><path fill="url(#ibC5tOb)" class="olr-q-b8n"/><path fill="url(#iaEmxXi)" class="olr-q-b8n"/></g><g filter="url(#ibYu9Ad)"><path fill="url(#ifwHi3f)" class="aq7z41bhg"/><path fill="url(#i20ZZ8H)" class="aq7z41bhg"/></g><g filter="url(#iFkuDyc)"><path fill="url(#iTsWwcb)" class="vw_q-xrhx"/><path fill="url(#iPfyFeY)" class="vw_q-xrhx"/><path fill="url(#ikmZume)" class="vw_q-xrhx"/><path fill="url(#i3VeYhe)" class="vw_q-xrhx"/><path fill="url(#iKdJLNU)" class="vw_q-xrhx"/></g><path fill="url(#iXtdrJe)" class="ik619zdfz"/><path fill="url(#iZzSMEd)" class="ik619zdfz"/><path fill="url(#iSe3NQY)" class="ik619zdfz"/><path fill="url(#i8ehSTc)" class="fc_rjnx2c"/><path fill="url(#iiAVyId)" class="fc_rjnx2c"/><g filter="url(#iBsjxAc)"><path class="p-92ym-hs"/></g><g filter="url(#imuELQe)"><path class="s0m073bgv"/></g><g filter="url(#iQqKdue)"><path fill="url(#ibgZBdd)" class="d34lxkbiu"/><path fill="url(#ieWsl4k)" class="d34lxkbiu"/><path fill="url(#iuac85d)" class="d34lxkbiu"/></g><g filter="url(#iM6dWFc)"><path fill="url(#iqa8UZd)" class="z61wejb8t"/></g><g filter="url(#ixTcOje)"><path fill="url(#ihSgKxL)" class="zve62ocxb"/></g><path class="airx03b_i"/><defs><radialGradient id="iFqpuyc" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.328 12.649)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iXqA5zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iuxoJ3d" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.26 4.22)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="i1y9B7l" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.119 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="i4TBK6b" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.954)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="iovfRsd" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.4 15.223)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="iS9ZDiI" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.792)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="iCVqgAe" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.338 17.892)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="iwb90Fe" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.267)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="iYlbYMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.642)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iX6SMcd" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.432 25.423)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="ielLZkb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.252 20.267)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="iE2SYiX" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.704)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="iLCWise" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.11)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="iGm40Le" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.173)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="ibWfH0n" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.861)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="ibeowCc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.454)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="iHmM1Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.07 21.2)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="iTXLUYj" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.845)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iBbC8ab" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.845)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iDtXXCY" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.896 58.94)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="iMieJUd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.6)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="iKEq6hc" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.12 15.923)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="inyLdJb" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.58)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="imDWS3c" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.837)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="is5rbYb" cx="0" cy="0" r="1" gradientTransform="rotate(13.799 -61.434 36.133)scale(.68782 .87718)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="iVaCY7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.358 16.486)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iqDO8xd" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 12.015 7.42)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="iuqiK1d" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 0 0 -4.84375 14.65 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="c5ehj6bcm"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="iCSSE4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.917)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="i4xyObx" cx="0" cy="0" r="1" gradientTransform="matrix(-3.3667 .90626 -1.59163 -5.9128 17.338 16.86)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="odam8hbyg"/><stop offset="1" class="du8_b9dvn"/></radialGradient><radialGradient id="iZEwBGb" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.522 11.535)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="iZVAlYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.776 16.97)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="iTblmxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.72)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="ieKcP5d" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.88 20.941)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iAPfeUd" cx="0" cy="0" r="1" gradientTransform="rotate(-29.297 36.806 -7.1)scale(.99044 .92102)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="iuUNfsy" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.182 16.688)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iJx5USM" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.52344 .50555 .83423 10.26 17.157)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="i1IxFBe" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.085 16.965)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="imJF0Zc" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.485)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="ia5AYhd" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 6.12 14.466)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iZG9K8b" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -1.444 26.543)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="i2DrNKd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0224 2.83266 -3.02734 1.09266 10.503 11.92)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="vr0hm_b5l"/><stop offset=".967" class="sqp-bsbql"/></radialGradient><radialGradient id="iKCfocb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 18.859 10.862)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iVCmRnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40256 6.10192 -2.24332 -.148 21.208 10.63)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="irRiS4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 13.96 9.682)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="ixOhB9J" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 18.54 9.27)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="ifkTpqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.43566 -11.9885 0 16.098 7.597)" gradientUnits="userSpaceOnUse"><stop offset=".782" class="oaywogbve"/><stop offset=".982" class="t8b03cb4c"/></radialGradient><radialGradient id="ijqfU6b" cx="0" cy="0" r="1" gradientTransform="rotate(-100.469 13.638 -.889)scale(2.38342 1.72741)" gradientUnits="userSpaceOnUse"><stop class="fyin37b4h"/><stop offset="1" class="butw9vr3n"/></radialGradient><radialGradient id="igg8ZNe" cx="0" cy="0" r="1" gradientTransform="rotate(57.505 -.994 19.73)scale(2.90848 .88801)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="a3qscz__i"/><stop offset="1" class="j5-9xeb5d"/></radialGradient><radialGradient id="iGsx6kU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.71897 10.1329 0 10.821 9.28)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iT58akb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63265 6.43634 0 20.912 9.28)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="ibC5tOb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10651 -1.44082 .76733 -2.187 20.157 3.004)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iaEmxXi" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 15.146 1.411)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="ifwHi3f" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80692 1.37358 -.3823 -1.05955 16.353 3.008)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="i20ZZ8H" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.38 -5.794)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iTsWwcb" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -7.368 86.323)scale(3.4792 1.94581)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iPfyFeY" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.072 -1.79)scale(4.28181 2.38793)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="ikmZume" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.5774 -.9364 20.56 8.318)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="i3VeYhe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.845 3.897)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="iKdJLNU" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.504 3.772)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iZzSMEd" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.669 9.96)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iSe3NQY" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.029 10.504)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iiAVyId" cx="0" cy="0" r="1" gradientTransform="matrix(-.76042 1.8125 -2.28859 -.96015 11.136 10.485)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="tswy2ibdj"/><stop offset=".959" class="kplkhtbsn"/></radialGradient><radialGradient id="ibgZBdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.285)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="d345q5kvq"/><stop offset=".878" class="q3r2vvb2e"/></radialGradient><radialGradient id="ieWsl4k" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 13.042)" gradientUnits="userSpaceOnUse"><stop class="icl8iab1q"/><stop offset="1" class="d-uipgb7e"/></radialGradient><radialGradient id="iuac85d" cx="0" cy="0" r="1" gradientTransform="rotate(147.848 11.138 6.613)scale(6.34862 12.6391)" gradientUnits="userSpaceOnUse"><stop class="x_gul429t"/><stop offset="1" class="vyoyvyblw"/></radialGradient><radialGradient id="iqa8UZd" cx="0" cy="0" r="1" gradientTransform="matrix(.46094 1.04688 -1.8385 .80948 18.291 9.165)" gradientUnits="userSpaceOnUse"><stop class="f21c62brn"/><stop offset="1" class="femkqfbis"/></radialGradient><radialGradient id="ihSgKxL" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 1.04688 -1.83849 -.8095 13.85 9.165)" gradientUnits="userSpaceOnUse"><stop class="f21c62brn"/><stop offset="1" class="femkqfbis"/></radialGradient><filter id="i4mXLlc" width="7.981" height="13.148" x="1.991" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/></filter><filter id="iTL3OTc" width="7.981" height="13.148" x="22.028" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/></filter><filter id="i38wezd" width="9.078" height="5.683" x="17.916" y="15.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/></filter><filter id="iCLTwNe" width="8.928" height="5.533" x="5.258" y="15.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/></filter><filter id="isTibMg" width="4.194" height="5.942" x="13.971" y="12.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/></filter><filter id="iYTaBco" width="3.465" height="3.465" x="14.33" y="22.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/></filter><filter id="i209rhc" width="10.72" height="12.542" x="10.988" y="4.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_995" result="effect2_innerShadow_4002_995"/></filter><filter id="iHAwKZd" width="13.891" height="7.06" x="9.087" y="6.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_995" stdDeviation=".375"/></filter><filter id="iIK5uCc" width="3.877" height="4.9" x="13.905" y="9.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_995" stdDeviation=".5"/></filter><filter id="iLFeRjc" width="2.077" height="3.1" x="15.112" y="9.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.564706 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/></filter><filter id="ismw7Pb" width="12.873" height="8.357" x="9.615" y="1.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_995" result="effect2_innerShadow_4002_995"/></filter><filter id="ibYu9Ad" width="6.584" height="5.992" x="10.018" y="2.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_995" stdDeviation=".125"/></filter><filter id="iFkuDyc" width="6.362" height="5.736" x="15.892" y="3.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_995" stdDeviation=".125"/></filter><filter id="iBsjxAc" width="1.329" height="2.379" x="10.018" y="9.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_995" stdDeviation=".125"/></filter><filter id="imuELQe" width="1.447" height="2.403" x="20.763" y="9.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_995" stdDeviation=".125"/></filter><filter id="iQqKdue" width="15.059" height="7.157" x="8.503" y="6.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.141176 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.301961 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_995" result="effect2_innerShadow_4002_995"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.246463 0 0 0 0 0.17575 0 0 0 0 0.249183 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_995" result="effect3_innerShadow_4002_995"/></filter><filter id="iM6dWFc" width="2.142" height="1.527" x="17.273" y="8.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.721569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/></filter><filter id="ixTcOje" width="2.142" height="1.527" x="12.726" y="8.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.721569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_995"/></filter><linearGradient id="ipb9C6d" x1="23.236" x2="22.979" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="ilLMcAb" x1="8.858" x2="8.994" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="iS32ave" x1="23.252" x2="23.486" y1="29.985" y2="29.985" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="i5sGDuc" x1="25.746" x2="20.292" y1="15.923" y2="20.134" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="iQmlBWX" x1="9.772" x2="9.772" y1="15.917" y2="20.704" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="irZlZhb" x1="9.772" x2="9.772" y1="15.548" y2="17.517" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="iJzI5Ge" x1="16.985" x2="15.947" y1="23.122" y2="24.026" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="iswSTLG" x1="21.415" x2="11.291" y1="5.199" y2="5.199" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iXtdrJe" x1="22.487" x2="21.28" y1="10.027" y2="12.203" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="i8ehSTc" x1="9.928" x2="11.059" y1="10.826" y2="10.603" gradientUnits="userSpaceOnUse"><stop class="em4l58mkc"/><stop offset="1" class="h02iueaoc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-supervillain" /></template>
<style>
.a--e2mwlv {
  stop-color: var(--svg-color--614b90, #614B90);
}

.a-lmuhb3j {
  stop-color: var(--svg-color--7560a8, #7560A8);
}

.a3qscz__i {
  stop-color: var(--svg-color--f19b2f, #F19B2F);
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.airx03b_i {
  fill: var(--svg-color--88004d, #88004D);
  d: path("M17.75 12.648c-.614.807-1.368.893-1.872.924c-.085.006-.12.105-.051.154c.377.27.857.293 1.342.09c.51-.213.733-.703.747-1.123c.003-.091-.11-.118-.165-.045");
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.apxwuphud {
  d: path("M20.912 12.112a1.64 1.64 0 0 0 .905-.309v.931c0 .893-.532 1.69-1.34 2.02c.17-.363.286-.759.345-1.18z");
}

.aq7z41bhg {
  d: path("m16.332 5.4l-.066-.136a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.34 1.512-3.34 3.379V8.5c-.34-.259-.769-.805-.769-1.688c0-1.072.782-1.613 1.28-1.96a2.5 2.5 0 0 0 .332-.252l.1-.105c.349-.37.971-1.031 2.059-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.892v1.485z");
}

.av5bbdb4i {
  stop-color: var(--svg-color--ff499d, #FF499D);
}

.b5r8fe9sv {
  stop-color: var(--svg-color--735ca8, #735CA8);
}

.bfw_o9sgk {
  stop-color: var(--svg-color--8977bc, #8977BC);
  stop-opacity: 0;
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bkplcs5-b {
  stop-color: var(--svg-color--615181, #615181);
  stop-opacity: 0;
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bozoj1btu {
  stop-color: var(--svg-color--e7547f, #E7547F);
  stop-opacity: 0;
}

.butw9vr3n {
  stop-color: var(--svg-color--ffcf43, #FFCF43);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c50kycc4s {
  stop-color: var(--svg-color--ff5292, #FF5292);
  stop-opacity: 0;
}

.c5ehj6bcm {
  stop-color: var(--svg-color--a61e39, #A61E39);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.cbuctgb-f {
  stop-color: var(--svg-color--dd225e, #DD225E);
  stop-opacity: 0;
}

.cgymddbwl {
  stop-color: var(--svg-color--3f2563, #3F2563);
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
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

.d-jm4nrou {
  stop-color: var(--svg-color--7757b7, #7757B7);
  stop-opacity: 0;
}

.d-uipgb7e {
  stop-color: var(--svg-color--48323e, #48323E);
  stop-opacity: 0;
}

.d345q5kvq {
  stop-color: var(--svg-color--603d60, #603D60);
}

.d34lxkbiu {
  d: path("m8.576 6.872l3.932 5.84a.75.75 0 0 0 1.185.074l1.761-2.012a.5.5 0 0 0 .104-.185c.098-.292.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.185l1.761 2.012a.75.75 0 0 0 1.185-.073l3.932-5.84c.212-.314-.069-.68-.43-.567L17.2 8.14a.6.6 0 0 0-.338.304c-.216.415-.578.625-.833.631c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.305L9.006 6.306c-.361-.113-.642.253-.43.566");
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

.dkr4vta7s {
  stop-color: var(--svg-color--8977bc, #8977BC);
}

.do8d1irdg {
  stop-color: var(--svg-color--e1658e, #E1658E);
}

.du8_b9dvn {
  stop-color: var(--svg-color--643b89, #643B89);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
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

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.ecn2fkbpq {
  stop-color: var(--svg-color--79659c, #79659C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.em4l58mkc {
  stop-color: var(--svg-color--dd892b, #DD892B);
}

.f_z9dccjp {
  d: path("m15.575 21.315l-2.98-4.595h6.946l-2.958 4.594a.6.6 0 0 1-1.008.001");
}

.f21c62brn {
  stop-color: var(--svg-color--ccfe8c, #CCFE8C);
}

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f9nu08mzt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
}

.fc_rjnx2c {
  d: path("M10.997 9.003a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.fd6px-b3x {
  stop-color: var(--svg-color--593f75, #593F75);
}

.fdilk9b4n {
  stop-color: var(--svg-color--977fd1, #977FD1);
}

.femkqfbis {
  stop-color: var(--svg-color--c6f58b, #C6F58B);
}

.fg2yxxizz {
  d: path("M23.083 15.964c0 .222-.249.316-.556.316c-.306 0-.555-.12-.555-.316a.555.555 0 1 1 1.11 0");
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

.fyin37b4h {
  stop-color: var(--svg-color--ffcf43, #FFCF43);
}

.fypjwijgc {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
}

.g2wrz_okq {
  stop-color: var(--svg-color--bb4566, #BB4566);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gmo59fbsi {
  d: path("M22.037 16.958c0 .292-.237.367-.53.367c-.291 0-.528-.075-.528-.367a.53.53 0 0 1 1.058 0");
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.h02iueaoc {
  stop-color: var(--svg-color--d37e25, #D37E25);
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hsuj-b9qt {
  d: path("M24.115 16.958c0 .21-.237.3-.529.3s-.53-.113-.53-.3a.53.53 0 1 1 1.06 0");
}

.hzf8hkb5j {
  fill: var(--svg-color--f6a218, #F6A218);
  d: path("m15.669 10.147l-.532 1.839c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.114-.407-.646-.407-.765 0");
}

.i3hug6b7s {
  stop-color: var(--svg-color--655586, #655586);
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.ib49rus2q {
  stop-color: var(--svg-color--72599f, #72599F);
  stop-opacity: 0;
}

.icl8iab1q {
  stop-color: var(--svg-color--48323e, #48323E);
}

.ie12c-fkv {
  stop-color: var(--svg-color--ee205c, #EE205C);
  stop-opacity: 0;
}

.iek0mvbvg {
  stop-color: var(--svg-color--563680, #563680);
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ik619zdfz {
  d: path("M20.973 12.203q.1-1.596.184-3.191a1.61 1.61 0 0 1-.184 3.19");
}

.irvd0gopv {
  d: path("M24.635 19.919c-.75 1.082-1.855 1.976-4.008 1.05c-1.836-.788-2.71-3.268-2.71-5.046l8.202.023c.653 0 .752.442.492.856a376 376 0 0 1-1.976 3.117");
}

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.j5-9xeb5d {
  stop-color: var(--svg-color--f19b2f, #F19B2F);
  stop-opacity: 0;
}

.jd2wixbxg {
  d: path("M8.861 18.142v11.843H4.588c.205-3.069.605-5.613 1.406-7.563c.772-1.881 1.77-3.268 2.867-4.28");
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.k-a516hzq {
  fill: var(--svg-color--f59529, #F59529);
  d: path("m15.565 10.343l-.635 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.543-.407-.662 0");
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kejp2n55e {
  stop-color: var(--svg-color--79659c, #79659C);
}

.klsvjl5ds {
  stop-color: var(--svg-color--7056ae, #7056AE);
}

.kplkhtbsn {
  stop-color: var(--svg-color--c97319, #C97319);
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

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.lmv51mb1h {
  d: path("M10.065 16.95c0 .293.237.367.53.367c.292 0 .529-.075.529-.367a.53.53 0 1 0-1.059 0");
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.m48igd19d {
  stop-color: var(--svg-color--735aa1, #735AA1);
}

.m9hq76bya {
  stop-color: var(--svg-color--64468e, #64468E);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
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

.n6ixpp1jb {
  stop-color: var(--svg-color--7da646, #7DA646);
}

.n7j357b5a {
  stop-color: var(--svg-color--230f39, #230F39);
  stop-opacity: 0;
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.oaywogbve {
  stop-color: var(--svg-color--fe9d3d, #FE9D3D);
  stop-opacity: 0;
}

.odam8hbyg {
  stop-color: var(--svg-color--835ac7, #835AC7);
}

.ogttk6b6n {
  stop-color: var(--svg-color--774ca5, #774CA5);
}

.olr-q-b8n {
  d: path("M20.906 4.22c.514.176.976.535 1.267 1.05a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.75 1.75 0 0 0-.667-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.513-3.341 3.38l.03 1.537a1.7 1.7 0 0 0-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.143-2.446a2.35 2.35 0 0 1 1.299-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.187.912-.187c.844 0 1.581.456 1.99 1.131c.307.51.79.88 1.352 1.073");
}

.p-92ym-hs {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M11.014 9.664a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.p63xbfaao {
  stop-color: var(--svg-color--85527f, #85527F);
  stop-opacity: 0;
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pbx1a_0-e {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.957c0 .22.248.315.555.315c.306 0 .555-.119.555-.315a.555.555 0 0 0-1.11 0");
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pnrkvto3p {
  d: path("M7.467 19.913c.75 1.082 1.856 1.976 4.008 1.051c1.836-.789 2.711-3.269 2.711-5.047l-8.203.024c-.652 0-.751.442-.492.855c.646 1.03 1.52 2.406 1.976 3.117");
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.ptuohkesm {
  stop-color: var(--svg-color--cd2172, #CD2172);
  stop-opacity: 0;
}

.q3r2vvb2e {
  stop-color: var(--svg-color--514853, #514853);
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

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r5lwd_9jp {
  fill: var(--svg-color--64417a, #64417A);
  d: path("M6.984 15.957c0 .22.249.315.555.315s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s0m073bgv {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M21.013 11.552q.058-.952.11-1.904a.956.956 0 0 1-.11 1.904");
}

.sdwnt9exm {
  d: path("M11.19 12.112a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.slx6fqref {
  stop-color: var(--svg-color--e1658e, #E1658E);
  stop-opacity: 0;
}

.sqp-bsbql {
  stop-color: var(--svg-color--c1511a, #C1511A);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t_0girb4l {
  d: path("M7.987 16.95c0 .211.237.3.53.3c.292 0 .529-.112.529-.3a.53.53 0 1 0-1.06 0");
}

.t3sh78bml {
  d: path("M25.118 15.964c0 .222-.249.316-.555.316s-.556-.12-.556-.316a.555.555 0 0 1 1.11 0");
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.t8b03cb4c {
  stop-color: var(--svg-color--d47a30, #D47A30);
}

.th4v7c7lc {
  d: path("M4.588 29.985h22.938c-.206-3.069-.606-5.613-1.406-7.563c-2.445-5.955-7.16-6.953-10.063-6.812c-2.904-.141-7.618.857-10.063 6.812c-.8 1.95-1.2 4.494-1.406 7.563");
}

.tswy2ibdj {
  stop-color: var(--svg-color--c97319, #C97319);
  stop-opacity: 0;
}

.tyoz-v6go {
  stop-color: var(--svg-color--cd2172, #CD2172);
}

.u05m0u9vr {
  stop-color: var(--svg-color--ae495e, #AE495E);
  stop-opacity: 0;
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.uc4vypayb {
  stop-color: var(--svg-color--8371ae, #8371AE);
}

.uhjz0cbil {
  stop-color: var(--svg-color--e62f68, #E62F68);
  stop-opacity: 0;
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

.uq-m7pb0g {
  stop-color: var(--svg-color--573a88, #573A88);
}

.uvjko3k9x {
  d: path("M6.984 15.957c0 .22.249.315.555.315s.556-.119.556-.315a.555.555 0 1 0-1.11 0");
}

.v_v98qact {
  stop-color: var(--svg-color--230f39, #230F39);
}

.vat9yt_ey {
  stop-color: var(--svg-color--614290, #614290);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vipjwwaoi {
  d: path("M23.252 18.142v11.843h4.274c-.206-3.069-.606-5.613-1.406-7.563c-.773-1.881-1.771-3.268-2.868-4.28");
}

.vr0hm_b5l {
  stop-color: var(--svg-color--e17e2c, #E17E2C);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vw_q-xrhx {
  d: path("m21.264 8.618l-.03-.63c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.136-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.188 2.082.517 2.902 1.051c1.745 1.138 1.44 3.189.52 4.154");
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wnzu6gyxf {
  cx: 16.063px;
  cy: 23.995px;
  r: 1.732px;
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
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

.x_gul429t {
  stop-color: var(--svg-color--6c587a, #6C587A);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xo7sfdbbq {
  d: path("m15.669 10.147l-.532 1.839c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.114-.407-.646-.407-.765 0");
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

.y5cz88bph {
  fill: var(--svg-color--d57e27, #D57E27);
  d: path("m9.897 8.202l3.235 4.805a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.152c.08-.24.253-.576.388-.576c.154 0 .313.336.393.576a.4.4 0 0 0 .085.152l1.45 1.656a.617.617 0 0 0 .975-.06l3.235-4.806c.174-.258-.057-.56-.354-.466l-4.821 1.51a.5.5 0 0 0-.278.25c-.178.341-.476.514-.685.52c-.21-.006-.503-.179-.68-.52a.5.5 0 0 0-.278-.25l-4.821-1.51c-.298-.093-.529.208-.354.466");
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
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

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z61wejb8t {
  d: path("m19.064 8.778l-1.608.593c-.154.057-.235.23-.147.367c.22.343.656.693 1.345.49c.65-.192.792-.815.755-1.257c-.014-.167-.188-.25-.345-.193");
}

.z8xki-b3f {
  d: path("M11.226 13.627a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418H14.33c-1.845 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
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

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zve62ocxb {
  d: path("m13.077 8.778l1.607.593c.154.057.236.23.147.367c-.22.343-.656.693-1.345.49c-.65-.192-.792-.815-.755-1.257c.014-.167.188-.25.346-.193");
}

.zxe--8tbm {
  stop-color: var(--svg-color--50387f, #50387F);
  stop-opacity: 0;
}

</style>
