<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i5qGoVY)"><path fill="url(#iUopVTP)" class="gt2gx2bio"/><path fill="url(#iXqA5zb)" class="gt2gx2bio"/></g><g filter="url(#i8o3YPd)"><path fill="url(#iuxoJ3d)" class="sb751abrh"/><path fill="url(#ifUZMNe)" class="sb751abrh"/></g><path fill="url(#i4TBK6b)" class="z-663abjc"/><path fill="url(#iovfRsd)" class="z-663abjc"/><path fill="url(#iS9ZDiI)" class="z-663abjc"/><path fill="url(#i1foxBc)" class="z-663abjc"/><path fill="url(#iCVqgAe)" class="z-663abjc"/><path fill="url(#iwb90Fe)" class="z-663abjc"/><path fill="url(#iYlbYMc)" class="z-663abjc"/><path fill="url(#ijK3uvT)" class="z-663abjc"/><path fill="url(#iX5Gmzd)" class="eor0twxxx"/><path fill="url(#imhkChc)" class="eor0twxxx"/><path fill="url(#iE2SYiX)" class="eor0twxxx"/><path fill="url(#iv5Z5Bc)" class="eor0twxxx"/><path fill="url(#iLCWise)" class="t8exe6wrr"/><path fill="url(#iGm40Le)" class="t8exe6wrr"/><path fill="url(#ibWfH0n)" class="t8exe6wrr"/><path fill="url(#ibeowCc)" class="t8exe6wrr"/><path fill="url(#iHmM1Fe)" class="mx-85jb1t"/><path fill="url(#iTXLUYj)" class="t0w0rqekg"/><path fill="url(#iBbC8ab)" class="azrkk3byv"/><g filter="url(#iIXDRrf)"><path fill="url(#iPO6Nic)" class="zbp0ozbsv"/><path fill="url(#idRboMJ)" class="zbp0ozbsv"/><path fill="url(#ivUDyye)" class="zbp0ozbsv"/><path fill="url(#ilNBzdF)" class="zbp0ozbsv"/></g><path class="ajn00ccsd"/><path fill="url(#inyLdJb)" class="ptsux4_gj"/><path fill="url(#imDWS3c)" class="ptsux4_gj"/><path class="e0i_c0zax"/><path fill="url(#imwEViV)" class="duue5wbir"/><g filter="url(#igDlbCd)"><path fill="url(#irP5cAb)" class="gr1-5henh"/><path fill="url(#irZlZhb)" class="gr1-5henh"/><path fill="url(#iVaCY7b)" class="gr1-5henh"/><path fill="url(#iqDO8xd)" class="gr1-5henh"/><path fill="url(#iuqiK1d)" class="gr1-5henh"/><path fill="url(#iI34C8c)" class="gr1-5henh"/></g><g filter="url(#iBWqyId)"><path fill="url(#i4xyObx)" class="wggtpctur"/></g><path fill="url(#iZEwBGb)" class="tjm6hrb4m"/><path fill="url(#ibHJk7b)" class="tjm6hrb4m"/><path fill="url(#iTblmxe)" class="r9_ojgb5f"/><path fill="url(#ieKcP5d)" class="f_i03rbpy"/><path fill="url(#iIvcxxb)" class="f_i03rbpy"/><path fill="url(#i0HK7fc)" class="ott1cnd8j"/><path fill="url(#i5Obtud)" class="ott1cnd8j"/><g filter="url(#ixA6Uld)"><circle fill="url(#ivk5jac)" class="hl0sk802z"/><circle fill="url(#icBHxnd)" class="hl0sk802z"/></g><ellipse fill="url(#iwB60Mb)" transform="rotate(-31.445 16.554 23.508)" class="d9pt9np5n"/><circle fill="url(#iIVsVEU)" class="spz-82b7z"/><g filter="url(#iEdm2uk)"><circle fill="url(#iIlD4nb)" class="lo3a_acnh"/></g><g filter="url(#iV6f1Tc)"><circle fill="url(#iJfQDPd)" class="xkk8eybzc"/><circle fill="url(#iL2wtOb)" class="xkk8eybzc"/></g><g filter="url(#ilc8Ioc)"><circle class="pd-cydg3m"/><circle fill="url(#iF5Wsjc)" class="terk_xbor"/><circle fill="url(#iA83Oed)" class="terk_xbor"/></g><path fill="url(#ig2XGMd)" class="m5_m798gb"/><path fill="url(#io0wByt)" class="m5_m798gb"/><path fill="url(#ijwnyzv)" class="m5_m798gb"/><path fill="url(#iEMVSvd)" class="m5_m798gb"/><path fill="url(#iJ3BWJb)" class="m5_m798gb"/><path fill="url(#ipMF1xd)" class="m5_m798gb"/><g filter="url(#ieBb1De)"><path class="pcsc3pbig"/><path fill="url(#i3TYaWk)" class="o41cl-b4g"/><path fill="url(#iJ847cc)" class="o41cl-b4g"/><path fill="url(#iI7cQdc)" class="o41cl-b4g"/><path fill="url(#iLtUVoJ)" class="o41cl-b4g"/><path fill="url(#iWWlpnJ)" class="o41cl-b4g"/><path fill="url(#iJ0Yj6c)" class="o41cl-b4g"/></g><path fill="url(#i0weI5P)" class="o41cl-b4g"/><path fill="url(#iOpsM7c)" class="o41cl-b4g"/><path fill="url(#iA4gKoe)" class="o41cl-b4g"/><g filter="url(#iYYA14b)"><path class="y0pxzj03t"/></g><g filter="url(#i39Y1Xb)"><path class="f4e3ww9un"/><path fill="url(#iLdUEOd)" class="fnr_qbcgq"/><path fill="url(#i3vngKd)" class="fnr_qbcgq"/><path fill="url(#iDBI9hU)" class="fnr_qbcgq"/></g><g filter="url(#iTL6t6V)"><path class="w6y0cibie"/></g><g filter="url(#iSiixzb)"><path fill="url(#ibgZBdd)" class="ql983pbok"/><path fill="url(#ieWsl4k)" class="ql983pbok"/><path fill="url(#iuac85d)" class="ql983pbok"/></g><g filter="url(#iJGiwJe)"><path fill="url(#iqa8UZd)" class="lp2vkg4nb"/></g><g filter="url(#i2jb3Le)"><path fill="url(#ihSgKxL)" class="i0bz3dbzf"/></g><path class="e79x119tr"/><defs><radialGradient id="iUopVTP" cx="0" cy="0" r="1" gradientTransform="rotate(-77.425 20.328 12.65)scale(12.4871 3.86791)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="iXqA5zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6437 5.87086 -1.1886 -.33278 5.881 24.642)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="iuxoJ3d" cx="0" cy="0" r="1" gradientTransform="rotate(-108.435 25.26 4.22)scale(14.6255 4.53031)" gradientUnits="userSpaceOnUse"><stop class="fd6px-b3x"/><stop offset="1" class="zblf_actk"/></radialGradient><radialGradient id="ifUZMNe" cx="0" cy="0" r="1" gradientTransform="matrix(1.6437 5.87086 -1.1886 .33278 26.118 24.643)" gradientUnits="userSpaceOnUse"><stop class="v_v98qact"/><stop offset="1" class="n7j357b5a"/></radialGradient><radialGradient id="i4TBK6b" cx="0" cy="0" r="1" gradientTransform="matrix(-7.65624 8.81247 -8.58004 -7.4543 21.15 19.954)" gradientUnits="userSpaceOnUse"><stop class="m48igd19d"/><stop offset="1" class="m9hq76bya"/></radialGradient><radialGradient id="iovfRsd" cx="0" cy="0" r="1" gradientTransform="rotate(123.254 3.4 15.223)scale(12.0566 23.4242)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="zojxemb8i"/><stop offset="1" class="fypjwijgc"/></radialGradient><radialGradient id="iS9ZDiI" cx="0" cy="0" r="1" gradientTransform="matrix(-6.03124 1.09998 -3.62517 -19.87702 24.15 22.792)" gradientUnits="userSpaceOnUse"><stop class="uc4vypayb"/><stop offset="1" class="ib49rus2q"/></radialGradient><radialGradient id="iCVqgAe" cx="0" cy="0" r="1" gradientTransform="matrix(.21874 4.4375 -3.52577 .1738 21.338 17.892)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="yhvjw36xj"/><stop offset="1" class="qf-zh-bgi"/></radialGradient><radialGradient id="iwb90Fe" cx="0" cy="0" r="1" gradientTransform="matrix(.34375 5.52507 -4.70428 .29269 10.588 17.267)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="kr4wgsbgo"/><stop offset=".991" class="vat9yt_ey"/></radialGradient><radialGradient id="iYlbYMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.34375 -.50337 0 8.838 20.642)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="i3hug6b7s"/><stop offset="1" class="bkplcs5-b"/></radialGradient><radialGradient id="iX5Gmzd" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -.1875 .66954 12.9444 23.431 25.423)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="cx3r1wb0p"/><stop offset="1" class="b5r8fe9sv"/></radialGradient><radialGradient id="imhkChc" cx="0" cy="0" r="1" gradientTransform="matrix(2.02342 3.79718 -2.02268 1.07783 23.251 20.267)" gradientUnits="userSpaceOnUse"><stop class="dkr4vta7s"/><stop offset="1" class="bfw_o9sgk"/></radialGradient><radialGradient id="iE2SYiX" cx="0" cy="0" r="1" gradientTransform="matrix(3.9375 -1.15625 3.32754 11.33163 23.588 25.704)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="j0a0weg0v"/><stop offset="1" class="a--e2mwlv"/></radialGradient><radialGradient id="iLCWise" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89844 -.93751 4.08965 -17.00586 8.861 27.11)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="klsvjl5ds"/><stop offset=".808" class="n5x1trblw"/></radialGradient><radialGradient id="iGm40Le" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.54958 0 9.213 20.173)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="iek0mvbvg"/><stop offset="1" class="ksp1sznci"/></radialGradient><radialGradient id="ibWfH0n" cx="0" cy="0" r="1" gradientTransform="matrix(-.46538 0 0 -10.5767 9.044 28.861)" gradientUnits="userSpaceOnUse"><stop offset=".473" class="a-lmuhb3j"/><stop offset="1" class="xrr4vbcci"/></radialGradient><radialGradient id="ibeowCc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 -.46874 1.19963 -13.91599 9.807 30.454)" gradientUnits="userSpaceOnUse"><stop offset=".919" class="e1q0bl71g"/><stop offset=".983" class="cvb6_wfpd"/></radialGradient><radialGradient id="iHmM1Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.75 3.76953 0 16.07 21.2)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f4t2p6bdy"/><stop offset=".921" class="n6ixpp1jb"/></radialGradient><radialGradient id="iTXLUYj" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 22.994 15.845)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="iBbC8ab" cx="0" cy="0" r="1" gradientTransform="matrix(-.92969 0 0 -.7732 25.03 15.845)" gradientUnits="userSpaceOnUse"><stop class="e9rx7xb_x"/><stop offset="1" class="mxm28cb7d"/></radialGradient><radialGradient id="idRboMJ" cx="0" cy="0" r="1" gradientTransform="rotate(20.097 -35.898 58.939)scale(3.67385 7.23049)" gradientUnits="userSpaceOnUse"><stop class="ajmnmmbez"/><stop offset="1" class="ie12c-fkv"/></radialGradient><radialGradient id="ivUDyye" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25043 3.70058 -.73486 -.44689 26.744 16.601)" gradientUnits="userSpaceOnUse"><stop class="yog48s40z"/><stop offset="1" class="c50kycc4s"/></radialGradient><radialGradient id="ilNBzdF" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 0 0 .79688 20.119 15.923)" gradientUnits="userSpaceOnUse"><stop class="ungg6q-mb"/><stop offset="1" class="bozoj1btu"/></radialGradient><radialGradient id="inyLdJb" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 .25757 -.32848 .46827 9.08 15.58)" gradientUnits="userSpaceOnUse"><stop class="f9nu08mzt"/><stop offset="1" class="y06th9bdt"/></radialGradient><radialGradient id="imDWS3c" cx="0" cy="0" r="1" gradientTransform="matrix(.956 0 0 1.08294 9.174 15.837)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yr3p0jbaj"/><stop offset="1" class="n1_6kac4r"/></radialGradient><radialGradient id="imwEViV" cx="0" cy="0" r="1" gradientTransform="rotate(13.799 -61.435 36.133)scale(.68782 .87718)" gradientUnits="userSpaceOnUse"><stop class="kejp2n55e"/><stop offset="1" class="ecn2fkbpq"/></radialGradient><radialGradient id="iVaCY7b" cx="0" cy="0" r="1" gradientTransform="matrix(2.72977 4.35939 -.30397 .19034 5.358 16.486)" gradientUnits="userSpaceOnUse"><stop class="do8d1irdg"/><stop offset="1" class="slx6fqref"/></radialGradient><radialGradient id="iqDO8xd" cx="0" cy="0" r="1" gradientTransform="rotate(-125.167 12.015 7.42)scale(3.52673 3.449)" gradientUnits="userSpaceOnUse"><stop class="e33ikws-z"/><stop offset="1" class="ll-hxrboz"/></radialGradient><radialGradient id="iuqiK1d" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 0 0 -4.84375 14.65 16.298)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="c5ehj6bcm"/><stop offset="1" class="cbuctgb-f"/></radialGradient><radialGradient id="iI34C8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66406 0 0 -.3962 12.572 15.918)" gradientUnits="userSpaceOnUse"><stop class="qsjdql87s"/><stop offset="1" class="u05m0u9vr"/></radialGradient><radialGradient id="i4xyObx" cx="0" cy="0" r="1" gradientTransform="matrix(-3.3667 .90626 -1.59163 -5.9128 17.338 16.86)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="odam8hbyg"/><stop offset="1" class="du8_b9dvn"/></radialGradient><radialGradient id="iZEwBGb" cx="0" cy="0" r="1" gradientTransform="rotate(147.753 8.522 11.535)scale(.93297 1.08283)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".796" class="zhe9zhdzx"/></radialGradient><radialGradient id="ibHJk7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 -.1328 .1252 -.75127 21.775 16.97)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="p63xbfaao"/><stop offset="1" class="qxsf0l9dp"/></radialGradient><radialGradient id="iTblmxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78906 .46094 -.5319 -.91052 23.963 16.72)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="fdilk9b4n"/><stop offset=".963" class="zhe9zhdzx"/></radialGradient><radialGradient id="ieKcP5d" cx="0" cy="0" r="1" gradientTransform="rotate(35.635 -21.88 20.941)scale(.89396 1.0943)" gradientUnits="userSpaceOnUse"><stop offset=".069" class="jipovxgfv"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="iIvcxxb" cx="0" cy="0" r="1" gradientTransform="matrix(.86375 -.48466 .4507 .80322 8.182 17.103)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="i0HK7fc" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 .5625 -.70389 .90919 10.181 16.689)" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset="1" class="ogttk6b6n"/></radialGradient><radialGradient id="i5Obtud" cx="0" cy="0" r="1" gradientTransform="rotate(-31.216 35.84 -9.784)scale(1.00998 .97546)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="k1yq73b8m"/><stop offset="1" class="qaycvn_cp"/></radialGradient><radialGradient id="ivk5jac" cx="0" cy="0" r="1" gradientTransform="rotate(114.286 1.084 16.965)scale(2.81128 2.59835)" gradientUnits="userSpaceOnUse"><stop class="av5bbdb4i"/><stop offset="1" class="l1led_brw"/></radialGradient><radialGradient id="icBHxnd" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 .8125 -1.6896 1.46215 14.713 22.486)" gradientUnits="userSpaceOnUse"><stop class="tyoz-v6go"/><stop offset="1" class="ptuohkesm"/></radialGradient><radialGradient id="iIVsVEU" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.624 10.624)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="mfkfu1nap"/></radialGradient><radialGradient id="iL2wtOb" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.19 10.359)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iF5Wsjc" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.776 11.446)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iA83Oed" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.818 10.624)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="ijwnyzv" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.59375 -9.8125 0 16.54 9.031)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset=".958" class="wfbk9ddhg"/></radialGradient><radialGradient id="iEMVSvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.396 9.351)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iJ3BWJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.834 9.317)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="ipMF1xd" cx="0" cy="0" r="1" gradientTransform="rotate(-113.999 9.426 .2)scale(4.99424 2.25579)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="uv4q9fbua"/><stop offset="1" class="xt7qzgb7y"/></radialGradient><radialGradient id="i3TYaWk" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43986 4.43352 -7.5396 -5.84979 19.744 2.903)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iI7cQdc" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 9.137 -1.937)scale(2.00292 .98368)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iLtUVoJ" cx="0" cy="0" r="1" gradientTransform="matrix(.85996 -1.96834 1.60534 .70136 20.279 8.885)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iWWlpnJ" cx="0" cy="0" r="1" gradientTransform="matrix(.99373 1.23303 -1.08867 .87739 15.272 2.014)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iJ0Yj6c" cx="0" cy="0" r="1" gradientTransform="matrix(1.45237 -3.03851 1.04984 .50181 20.24 6.4)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="i0weI5P" cx="0" cy="0" r="1" gradientTransform="matrix(.26142 1.01586 -1.67013 .42978 16.743 2.014)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iOpsM7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.108 1.60044 -3.3305 2.30572 11.662 3.277)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iA4gKoe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.21429 3.2501 -4.0668 -9.02713 17.202 6.256)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="ibgZBdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.38819 -12.4445 0 16.032 6.285)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="d345q5kvq"/><stop offset=".878" class="q3r2vvb2e"/></radialGradient><radialGradient id="ieWsl4k" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -4.36884 3.96591 -1.07796 13.025 13.042)" gradientUnits="userSpaceOnUse"><stop class="icl8iab1q"/><stop offset="1" class="d-uipgb7e"/></radialGradient><radialGradient id="iuac85d" cx="0" cy="0" r="1" gradientTransform="rotate(147.848 11.138 6.613)scale(6.34862 12.6391)" gradientUnits="userSpaceOnUse"><stop class="x_gul429t"/><stop offset="1" class="vyoyvyblw"/></radialGradient><radialGradient id="iqa8UZd" cx="0" cy="0" r="1" gradientTransform="matrix(.46094 1.04688 -1.8385 .80948 18.291 9.165)" gradientUnits="userSpaceOnUse"><stop class="f21c62brn"/><stop offset="1" class="femkqfbis"/></radialGradient><radialGradient id="ihSgKxL" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 1.04688 -1.83849 -.8095 13.85 9.165)" gradientUnits="userSpaceOnUse"><stop class="f21c62brn"/><stop offset="1" class="femkqfbis"/></radialGradient><filter id="i5qGoVY" width="7.981" height="13.148" x="1.991" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/></filter><filter id="i8o3YPd" width="7.981" height="13.148" x="22.028" y="16.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/></filter><filter id="iIXDRrf" width="9.078" height="5.683" x="17.916" y="15.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.101961 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/></filter><filter id="igDlbCd" width="8.928" height="5.533" x="5.258" y="15.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.113725 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/></filter><filter id="iBWqyId" width="4.194" height="5.942" x="13.971" y="12.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/></filter><filter id="ixA6Uld" width="3.465" height="3.465" x="14.33" y="22.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.145098 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/></filter><filter id="iEdm2uk" width="2.992" height="2.992" x="9.8" y="9.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_997" stdDeviation=".25"/></filter><filter id="iV6f1Tc" width="3.592" height="3.592" x="19.147" y="8.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/></filter><filter id="ilc8Ioc" width="2.992" height="2.992" x="19.322" y="9.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_997" stdDeviation=".25"/></filter><filter id="ieBb1De" width="12.614" height="8.301" x="9.741" y="1.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_997" result="effect2_innerShadow_4002_997"/></filter><filter id="iYYA14b" width="3.262" height="4.184" x="14.178" y="9.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_997" stdDeviation=".375"/></filter><filter id="i39Y1Xb" width="2.379" height="3.184" x="14.858" y="9.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_997" stdDeviation=".125"/></filter><filter id="iTL6t6V" width="13.891" height="7.06" x="9.087" y="6.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_997" stdDeviation=".375"/></filter><filter id="iSiixzb" width="15.059" height="7.157" x="8.503" y="6.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.141176 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.301961 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_997" result="effect2_innerShadow_4002_997"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.246463 0 0 0 0 0.17575 0 0 0 0 0.249183 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_997" result="effect3_innerShadow_4002_997"/></filter><filter id="iJGiwJe" width="2.142" height="1.527" x="17.273" y="8.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.721569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/></filter><filter id="i2jb3Le" width="2.142" height="1.527" x="12.726" y="8.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.721569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_997"/></filter><linearGradient id="i1foxBc" x1="23.236" x2="22.978" y1="29.986" y2="29.986" gradientUnits="userSpaceOnUse"><stop class="y-so25ixd"/><stop offset="1" class="zxe--8tbm"/></linearGradient><linearGradient id="ijK3uvT" x1="8.857" x2="8.994" y1="29.986" y2="29.986" gradientUnits="userSpaceOnUse"><stop class="cgymddbwl"/><stop offset="1" class="gn957lbyv"/></linearGradient><linearGradient id="iv5Z5Bc" x1="23.252" x2="23.486" y1="29.986" y2="29.986" gradientUnits="userSpaceOnUse"><stop class="uq-m7pb0g"/><stop offset="1" class="d-jm4nrou"/></linearGradient><linearGradient id="iPO6Nic" x1="25.745" x2="20.292" y1="15.923" y2="20.135" gradientUnits="userSpaceOnUse"><stop class="lt42vtw3b"/><stop offset="1" class="xjh9cc18k"/></linearGradient><linearGradient id="irP5cAb" x1="9.772" x2="9.772" y1="15.918" y2="20.704" gradientUnits="userSpaceOnUse"><stop class="ujur1qtze"/><stop offset="1" class="ctoai6naw"/></linearGradient><linearGradient id="irZlZhb" x1="9.772" x2="9.772" y1="15.548" y2="17.517" gradientUnits="userSpaceOnUse"><stop offset=".071" class="g2wrz_okq"/><stop offset="1" class="uhjz0cbil"/></linearGradient><linearGradient id="iwB60Mb" x1="16.985" x2="15.947" y1="23.123" y2="24.027" gradientUnits="userSpaceOnUse"><stop offset=".453" class="vc--wpv5i"/><stop offset=".905" class="stui2mbih"/></linearGradient><linearGradient id="iIlD4nb" x1="11.296" x2="10.654" y1="10.903" y2="10.903" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iJfQDPd" x1="21.905" x2="21.086" y1="9.531" y2="12.07" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="ig2XGMd" x1="20.088" x2="12.444" y1="11.014" y2="12.153" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="io0wByt" x1="10.647" x2="12.962" y1="13.712" y2="13.41" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iJ847cc" x1="11.182" x2="14.087" y1="10.356" y2="5.197" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iLdUEOd" x1="15.183" x2="16.122" y1="11.673" y2="11.673" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="i3vngKd" x1="16.987" x2="15.96" y1="11.996" y2="11.982" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iDBI9hU" x1="16.242" x2="16.242" y1="12.739" y2="12.166" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-supervillain" /></template>
<style>
.a--e2mwlv {
  stop-color: var(--svg-color--614b90, #614B90);
}

.a-lmuhb3j {
  stop-color: var(--svg-color--7560a8, #7560A8);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.ajmnmmbez {
  stop-color: var(--svg-color--ee205c, #EE205C);
}

.ajn00ccsd {
  fill: var(--svg-color--5c396f, #5C396F);
  d: path("M9.02 15.957c0 .221.248.315.555.315c.306 0 .555-.118.555-.315a.555.555 0 0 0-1.11 0");
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.av5bbdb4i {
  stop-color: var(--svg-color--ff499d, #FF499D);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.azrkk3byv {
  d: path("M25.118 15.965c0 .22-.249.315-.555.315s-.556-.119-.556-.315a.555.555 0 0 1 1.11 0");
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

.c50kycc4s {
  stop-color: var(--svg-color--ff5292, #FF5292);
  stop-opacity: 0;
}

.c5ehj6bcm {
  stop-color: var(--svg-color--a61e39, #A61E39);
}

.cbuctgb-f {
  stop-color: var(--svg-color--dd225e, #DD225E);
  stop-opacity: 0;
}

.cgymddbwl {
  stop-color: var(--svg-color--3f2563, #3F2563);
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
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

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.d9pt9np5n {
  cx: 16.554px;
  cy: 23.508px;
  rx: 0.552px;
  ry: 0.695px;
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

.duue5wbir {
  d: path("M6.984 15.957c0 .221.249.315.555.315s.556-.118.556-.315a.555.555 0 1 0-1.11 0");
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e0i_c0zax {
  fill: var(--svg-color--64417a, #64417A);
  d: path("M6.984 15.957c0 .221.249.315.555.315s.556-.118.556-.315a.555.555 0 1 0-1.11 0");
}

.e1q0bl71g {
  stop-color: var(--svg-color--5f4d85, #5F4D85);
  stop-opacity: 0;
}

.e33ikws-z {
  stop-color: var(--svg-color--ff4574, #FF4574);
}

.e79x119tr {
  fill: var(--svg-color--88004d, #88004D);
  d: path("M17.75 12.648c-.614.807-1.368.893-1.872.925c-.085.005-.12.104-.051.154c.377.269.857.292 1.342.09c.51-.213.733-.703.747-1.123c.003-.092-.11-.119-.165-.046");
}

.e9rx7xb_x {
  stop-color: var(--svg-color--967bc2, #967BC2);
}

.ecn2fkbpq {
  stop-color: var(--svg-color--79659c, #79659C);
  stop-opacity: 0;
}

.eor0twxxx {
  d: path("M23.252 18.143v11.843h4.273c-.205-3.07-.605-5.613-1.406-7.564c-.772-1.88-1.77-3.267-2.867-4.28");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.f_i03rbpy {
  d: path("M7.987 16.95c0 .212.237.301.529.301s.53-.113.53-.3a.53.53 0 1 0-1.06 0");
}

.f21c62brn {
  stop-color: var(--svg-color--ccfe8c, #CCFE8C);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f4e3ww9un {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.665 10.338l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.378-.645-.378-.765 0");
}

.f4t2p6bdy {
  stop-color: var(--svg-color--a5ee69, #A5EE69);
}

.f9nu08mzt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
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

.fnr_qbcgq {
  d: path("m15.665 10.338l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.378-.645-.378-.765 0");
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

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gn957lbyv {
  stop-color: var(--svg-color--3f2563, #3F2563);
  stop-opacity: 0;
}

.gr1-5henh {
  d: path("M7.467 19.914c.75 1.082 1.855 1.976 4.008 1.05c1.836-.788 2.71-3.268 2.71-5.046l-8.202.023c-.653 0-.752.442-.492.856a374 374 0 0 0 1.976 3.116");
}

.gt2gx2bio {
  d: path("M1.99 29.986h3.532l4.25-8.75l-3.648-4.399C2.71 21.275 1.99 27.22 1.99 29.986");
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hl0sk802z {
  cx: 16.062px;
  cy: 23.995px;
  r: 1.732px;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i0bz3dbzf {
  d: path("m13.077 8.779l1.607.592c.154.057.236.23.147.368c-.22.342-.656.692-1.345.489c-.65-.192-.792-.814-.755-1.257c.014-.167.188-.25.346-.192");
}

.i3hug6b7s {
  stop-color: var(--svg-color--655586, #655586);
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

.j0a0weg0v {
  stop-color: var(--svg-color--614b90, #614B90);
  stop-opacity: 0;
}

.jipovxgfv {
  stop-color: var(--svg-color--7d64a6, #7D64A6);
}

.k1yq73b8m {
  stop-color: var(--svg-color--67416e, #67416E);
  stop-opacity: 0;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
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

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l1led_brw {
  stop-color: var(--svg-color--df1d5a, #DF1D5A);
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.ll-hxrboz {
  stop-color: var(--svg-color--ff4574, #FF4574);
  stop-opacity: 0;
}

.lo3a_acnh {
  cx: 11.296px;
  cy: 10.624px;
  r: 0.996px;
}

.lp2vkg4nb {
  d: path("m19.064 8.779l-1.608.592c-.154.057-.235.23-.147.368c.22.342.656.692 1.345.489c.65-.192.792-.814.755-1.257c-.014-.167-.188-.25-.345-.192");
}

.lt42vtw3b {
  stop-color: var(--svg-color--ff3880, #FF3880);
}

.m48igd19d {
  stop-color: var(--svg-color--735aa1, #735AA1);
}

.m5_m798gb {
  d: path("M10.943 10.01a30 30 0 0 1-.058-1.44c0-.266.107-.587.322-.747l.161-.16c.269-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.918.427c.215.053.43.267.43.534v.854c0 .32.161.64.376.854c.502.352.471.546.43.961c-.014.129-.054 1.196-.09 1.441l-.266 3.962c-.16 1.772-1.553 3.006-3.213 3.006h-3.214c-1.714 0-3.053-1.234-3.213-3.006z");
}

.m9hq76bya {
  stop-color: var(--svg-color--64468e, #64468E);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mfkfu1nap {
  stop-color: var(--svg-color--d17d22, #D17D22);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
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

.n6ixpp1jb {
  stop-color: var(--svg-color--7da646, #7DA646);
}

.n7j357b5a {
  stop-color: var(--svg-color--230f39, #230F39);
  stop-opacity: 0;
}

.o41cl-b4g {
  d: path("m20.871 4.14l.43.213c.752.374 1.181 1.228 1.02 2.136l-.59 3.043c-.053.314-.261.525-.573.533c.035-.504.069-1.317.082-1.446c.043-.433-.025-.56-.422-.956c-.215-.213-.376-.534-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.918.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.324.495-.324.762c.014.156.035 1.052.06 1.425a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082c1.015-.444 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.2-.32c.538.16 1.128.16 1.665 0c.806-.267 1.718-.053 2.363.534l.805.8c.215.267.483.428.805.588");
}

.odam8hbyg {
  stop-color: var(--svg-color--835ac7, #835AC7);
}

.ogttk6b6n {
  stop-color: var(--svg-color--774ca5, #774CA5);
}

.ott1cnd8j {
  d: path("M10.065 16.95c0 .293.237.368.53.368c.291 0 .528-.075.528-.367a.53.53 0 1 0-1.058 0");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p63xbfaao {
  stop-color: var(--svg-color--85527f, #85527F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pcsc3pbig {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m20.871 4.14l.43.213c.752.374 1.181 1.228 1.02 2.136l-.59 3.043c-.053.314-.261.525-.573.533c.035-.504.069-1.317.082-1.446c.043-.433-.025-.56-.422-.956c-.215-.213-.376-.534-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.918.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.324.495-.324.762c.014.156.035 1.052.06 1.425a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082c1.015-.444 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.2-.32c.538.16 1.128.16 1.665 0c.806-.267 1.718-.053 2.363.534l.805.8c.215.267.483.428.805.588");
}

.pd-cydg3m {
  cx: 20.818px;
  cy: 10.624px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.ptsux4_gj {
  d: path("M9.02 15.957c0 .221.248.315.555.315c.306 0 .555-.118.555-.315a.555.555 0 0 0-1.11 0");
}

.ptuohkesm {
  stop-color: var(--svg-color--cd2172, #CD2172);
  stop-opacity: 0;
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q3r2vvb2e {
  stop-color: var(--svg-color--514853, #514853);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qaycvn_cp {
  stop-color: var(--svg-color--67416e, #67416E);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qf-zh-bgi {
  stop-color: var(--svg-color--755da2, #755DA2);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.ql983pbok {
  d: path("m8.576 6.872l3.932 5.84a.75.75 0 0 0 1.185.074l1.761-2.012a.5.5 0 0 0 .104-.185c.098-.291.307-.7.471-.7c.188 0 .38.409.478.7a.5.5 0 0 0 .104.185l1.761 2.012a.75.75 0 0 0 1.185-.073l3.932-5.84c.212-.314-.069-.68-.43-.567L17.2 8.142a.6.6 0 0 0-.338.304c-.216.414-.578.624-.833.63c-.254-.006-.61-.216-.826-.63a.6.6 0 0 0-.338-.304L9.006 6.306c-.361-.113-.642.253-.43.566");
}

.qsjdql87s {
  stop-color: var(--svg-color--ae495e, #AE495E);
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qxsf0l9dp {
  stop-color: var(--svg-color--85527f, #85527F);
}

.r9_ojgb5f {
  d: path("M24.115 16.958c0 .211-.237.301-.53.301c-.291 0-.529-.113-.529-.3a.53.53 0 0 1 1.06 0");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sb751abrh {
  d: path("M30.01 29.986h-3.532l-4.25-8.75l3.648-4.399c3.414 4.438 4.133 10.383 4.133 13.149");
}

.slx6fqref {
  stop-color: var(--svg-color--e1658e, #E1658E);
  stop-opacity: 0;
}

.spz-82b7z {
  cx: 11.295px;
  cy: 10.624px;
  r: 1.671px;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t0w0rqekg {
  d: path("M23.083 15.965c0 .22-.249.315-.556.315c-.306 0-.555-.119-.555-.315a.555.555 0 1 1 1.11 0");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.t8exe6wrr {
  d: path("M8.861 18.143v11.843H4.588c.205-3.07.605-5.613 1.406-7.564c.772-1.88 1.77-3.267 2.867-4.28");
}

.terk_xbor {
  cx: 20.818px;
  cy: 10.624px;
  r: 0.996px;
}

.tjm6hrb4m {
  d: path("M22.037 16.958c0 .293-.237.368-.53.368c-.292 0-.529-.075-.529-.368a.53.53 0 0 1 1.059 0");
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tyoz-v6go {
  stop-color: var(--svg-color--cd2172, #CD2172);
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

.ujur1qtze {
  stop-color: var(--svg-color--db2a69, #DB2A69);
}

.ungg6q-mb {
  stop-color: var(--svg-color--e7547f, #E7547F);
}

.uq-m7pb0g {
  stop-color: var(--svg-color--573a88, #573A88);
}

.uv4q9fbua {
  stop-color: var(--svg-color--da8d1b, #DA8D1B);
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

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vyoyvyblw {
  stop-color: var(--svg-color--6c587a, #6C587A);
  stop-opacity: 0;
}

.w6y0cibie {
  fill: var(--svg-color--d57e27, #D57E27);
  d: path("m9.897 8.202l3.235 4.806a.617.617 0 0 0 .975.06l1.45-1.655a.4.4 0 0 0 .085-.152c.08-.24.253-.577.388-.577c.154 0 .313.337.393.577a.4.4 0 0 0 .085.152l1.45 1.655a.617.617 0 0 0 .975-.06l3.235-4.806c.174-.258-.057-.559-.354-.466l-4.821 1.51a.5.5 0 0 0-.278.25c-.178.342-.476.515-.685.52c-.21-.005-.503-.178-.68-.52a.5.5 0 0 0-.278-.25l-4.821-1.51c-.298-.093-.529.208-.354.466");
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wfbk9ddhg {
  stop-color: var(--svg-color--db7221, #DB7221);
}

.wggtpctur {
  d: path("M13.971 15.075a2.097 2.097 0 1 1 4.194 0v1.548c0 1.37-.938 2.097-2.097 2.097c-1.158 0-2.097-.695-2.097-2.097z");
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x_gul429t {
  stop-color: var(--svg-color--6c587a, #6C587A);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xjh9cc18k {
  stop-color: var(--svg-color--ff3669, #FF3669);
}

.xkk8eybzc {
  cx: 20.818px;
  cy: 10.624px;
  r: 1.671px;
}

.xrr4vbcci {
  stop-color: var(--svg-color--7560a8, #7560A8);
  stop-opacity: 0;
}

.xt7qzgb7y {
  stop-color: var(--svg-color--feaf22, #FEAF22);
  stop-opacity: 0;
}

.y-so25ixd {
  stop-color: var(--svg-color--50387f, #50387F);
}

.y06th9bdt {
  stop-color: var(--svg-color--6b5b8d, #6B5B8D);
  stop-opacity: 0;
}

.y0pxzj03t {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.772 10.501l-.82 1.702c-.103.35.142.7.488.7h.738c.346 0 .59-.356.488-.7l-.498-1.702c-.107-.377-.284-.377-.396 0");
}

.yhvjw36xj {
  stop-color: var(--svg-color--563079, #563079);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yog48s40z {
  stop-color: var(--svg-color--ff5292, #FF5292);
}

.yr3p0jbaj {
  stop-color: var(--svg-color--5d3970, #5D3970);
  stop-opacity: 0;
}

.z-663abjc {
  d: path("M4.588 29.986h22.937c-.205-3.07-.605-5.613-1.406-7.564c-2.444-5.955-7.159-6.953-10.062-6.811c-2.904-.142-7.619.856-10.063 6.811c-.8 1.95-1.2 4.494-1.406 7.564");
}

.zblf_actk {
  stop-color: var(--svg-color--372543, #372543);
}

.zbp0ozbsv {
  d: path("M24.635 19.92c-.75 1.081-1.856 1.975-4.008 1.05c-1.836-.789-2.711-3.269-2.711-5.047l8.203.024c.652 0 .752.442.492.855c-.646 1.03-1.52 2.406-1.976 3.117");
}

.zhe9zhdzx {
  stop-color: var(--svg-color--7a4c9c, #7A4C9C);
}

.zojxemb8i {
  stop-color: var(--svg-color--5b3e84, #5B3E84);
  stop-opacity: 0;
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zxe--8tbm {
  stop-color: var(--svg-color--50387f, #50387F);
  stop-opacity: 0;
}

</style>
