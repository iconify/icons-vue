<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iYvXCsb)"><path class="olsg4hb9z"/><path fill="url(#iVnLcBc)" class="afzezoczn"/><path fill="url(#ilmqlIe)" class="afzezoczn"/><path fill="url(#ipIGcbv)" class="afzezoczn"/><path fill="url(#izNnGCK)" class="afzezoczn"/></g><g filter="url(#iJk6L0b)"><path class="vitxoz2-x"/></g><g filter="url(#iMjHsab)"><path fill="url(#iiqUFBe)" class="m56ub07gi"/><path fill="url(#iYAIflb)" class="m56ub07gi"/><path fill="url(#iO434le)" class="m56ub07gi"/></g><g filter="url(#idt55Fs)"><path fill="url(#iajLbrc)" class="fygum0ndx"/><path fill="url(#iiO0l8d)" class="fygum0ndx"/></g><g filter="url(#i7wHkxd)"><path stroke="url(#iYyQBod)" class="iagna2bvo"/></g><g filter="url(#ix6OApb)"><path stroke="url(#iLUOnPH)" class="dsv_opieh"/></g><g filter="url(#iZJBZ3c)"><path stroke="url(#iOKMflT)" class="zmvga4bhq"/></g><path fill="url(#i3MAvNV)" class="zzd-j_97z"/><path fill="url(#iV1aTtP)" class="qd9b8r05y"/><g filter="url(#iTSSaJc)"><path fill="url(#ik6Pcdb)" class="r2yxhcjfl"/><path fill="url(#idVBYnd)" class="r2yxhcjfl"/></g><path fill="url(#iHrTIcK)" class="r2yxhcjfl"/><path fill="url(#i8QNZgd)" class="r2yxhcjfl"/><path fill="url(#izZZCKe)" class="r2yxhcjfl"/><path fill="url(#iB0v0ub)" class="r2yxhcjfl"/><path fill="url(#is8ombc)" class="r2yxhcjfl"/><path fill="url(#iSAV1Ib)" class="r2yxhcjfl"/><path fill="url(#iIqr5ue)" class="r2yxhcjfl"/><g filter="url(#isgsKed)"><path class="o8g716qws"/></g><g filter="url(#i21MWKv)"><path class="k-5y-nbih"/><path fill="url(#i2O41Ic)" class="f0ohsabjz"/><path fill="url(#ipY3NId)" class="f0ohsabjz"/><path fill="url(#iIfJdBc)" class="f0ohsabjz"/><path fill="url(#iGW23Mb)" class="f0ohsabjz"/><path fill="url(#iGYAAic)" class="f0ohsabjz"/></g><path fill="url(#i9trg6c)" class="f0ohsabjz"/><path fill="url(#iiCTCvb)" class="f0ohsabjz"/><g filter="url(#iqaGWMd)"><path stroke="url(#iksgqDd)" class="mtd419brd"/></g><path fill="url(#iilGJqb)" class="m2co8ibdp"/><g filter="url(#iMzQS2U)"><path fill="url(#ihKCVPb)" class="xhwuyccef"/><path fill="url(#i56I30d)" class="xhwuyccef"/><path fill="url(#irDg4he)" class="xhwuyccef"/><path fill="url(#iauYtHb)" class="xhwuyccef"/><path fill="url(#igJtKiW)" class="xhwuyccef"/></g><g filter="url(#iYYe1db)"><path class="vkgfzqx5q"/></g><g filter="url(#iAGCPGe)"><path class="a6zzhdb-b"/></g><g filter="url(#i8x8xvb)"><path class="acwz0eb8o"/><path fill="url(#isZqhIe)" class="mrc1www1l"/><path fill="url(#iRsY8od)" class="mrc1www1l"/></g><g filter="url(#iyss4yd)"><path class="lyglqcbey"/><path fill="url(#imMm1ib)" class="fdpsqp4nn"/><path fill="url(#iRiyrZb)" class="fdpsqp4nn"/></g><path class="v1lpopbju"/><path fill="url(#iPALKZb)" class="x2wzb6b0f"/><path class="mnryjhdzq"/><g filter="url(#iBUWONc)"><path class="ba0qpdb6z"/><path fill="url(#iiBUVTc)" class="bln9d_bpn"/></g><g filter="url(#iQMwdBf)"><path fill="url(#ir0l5Be)" class="pdfzhccus"/></g><path class="y3-5caior"/><path fill="url(#iIhaQib)" class="dskl7d_tu"/><path class="h99bv8gma"/><g filter="url(#ia8xZZC)"><path fill="url(#iJu8wLt)" class="zvu5-bczw"/></g><g filter="url(#i0Oezgc)"><ellipse transform="rotate(-27.914 16.271 8.726)" class="k7mpzkb9f"/><ellipse fill="url(#iDQ2SXb)" transform="rotate(-27.914 16.271 8.726)" class="c8y-ucoim"/></g><path fill="url(#iwz230b)" class="eb1a7s11t"/><path fill="url(#ixZLQVQ)" class="eb1a7s11t"/><path fill="url(#iNOIMad)" class="eb1a7s11t"/><path fill="url(#iyJRh0d)" class="eb1a7s11t"/><path fill="url(#ihbGPec)" class="zx-2c3btz"/><path fill="url(#inKr5Cb)" class="zx-2c3btz"/><g filter="url(#iPCmdme)"><path fill="url(#iuZc0Hc)" class="b0o7qyb_k"/></g><g filter="url(#iKSUQEc)"><path fill="url(#i6TCppd)" class="s6g7h-5ni"/></g><g filter="url(#iKZS7Bc)"><path class="p5xnx_9wf"/></g><g filter="url(#iA9o6VN)"><path class="llbkdob_q"/></g><g filter="url(#ig7ftkH)"><path class="lv92e9blh"/></g><g filter="url(#iwrlyHc)"><path stroke="url(#isJkioe)" class="q4wz22bch"/></g><defs><radialGradient id="iVnLcBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.2441 14.467 0 14.97 29.706)" gradientUnits="userSpaceOnUse"><stop class="i0nsp7bni"/><stop offset="1" class="j9mdirbao"/></radialGradient><radialGradient id="ilmqlIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.36327 -1.99342 2.97247 -.54169 20.997 15.767)" gradientUnits="userSpaceOnUse"><stop class="y8skcxtgz"/><stop offset="1" class="j0n9-bc_s"/></radialGradient><radialGradient id="ipIGcbv" cx="0" cy="0" r="1" gradientTransform="scale(2.6875 7.0625)rotate(90 2.3 5.378)" gradientUnits="userSpaceOnUse"><stop class="le_3nbbjw"/><stop offset="1" class="imi34--zw"/></radialGradient><radialGradient id="izNnGCK" cx="0" cy="0" r="1" gradientTransform="matrix(-6.39747 2.14876 -.75252 -2.24047 18.813 13.594)" gradientUnits="userSpaceOnUse"><stop offset=".449" class="vp7op3b3o"/><stop offset="1" class="akwhn1mys"/></radialGradient><radialGradient id="iajLbrc" cx="0" cy="0" r="1" gradientTransform="rotate(115.321 5.932 15.47)scale(4.28183 3.28478)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="l863e7bwo"/><stop offset="1" class="h-d21x52g"/></radialGradient><radialGradient id="iiO0l8d" cx="0" cy="0" r="1" gradientTransform="rotate(118.72 6.282 14.782)scale(2.6272 1.65249)" gradientUnits="userSpaceOnUse"><stop class="xhl3qijdh"/><stop offset="1" class="phlxv6bym"/></radialGradient><radialGradient id="i3MAvNV" cx="0" cy="0" r="1" gradientTransform="matrix(.66382 1.7904 -2.12687 .78857 22.66 10.457)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iV1aTtP" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -28.954 48.058)scale(1.37207 4.23294)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="ik6Pcdb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.63472 0 0 -8.19877 20.935 9.623)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="idVBYnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.54539 2.55587 -2.11008 -1.27585 20.598 5.209)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="i8QNZgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.01509 6.53312 0 18.43 15.288)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="izZZCKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.01806 1.25985 0 20.616 8.46)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iB0v0ub" cx="0" cy="0" r="1" gradientTransform="matrix(.00348 -.97013 1.05572 .0038 16.407 8.5)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="is8ombc" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 10.58 5.588)scale(7.54706 19.2789)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iSAV1Ib" cx="0" cy="0" r="1" gradientTransform="matrix(3.00164 -2.58558 .76374 .88664 12.425 7.2)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iIqr5ue" cx="0" cy="0" r="1" gradientTransform="matrix(-.20803 2.21409 -.88506 -.08316 23.362 7.037)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="ipY3NId" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2164 -.68014 0 18.86 10.83)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iGW23Mb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34856 .6183 -.99366 -2.16725 18.963 10.324)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iiCTCvb" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 7.398 8.805)scale(1.57128 2.26774)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="iilGJqb" cx="0" cy="0" r="1" gradientTransform="matrix(1.93443 -.95102 3.82618 7.78267 18.011 12.835)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i56I30d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.10408 7.84985 0 13.81 7.059)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="irDg4he" cx="0" cy="0" r="1" gradientTransform="matrix(.1011 -2.22748 3.94666 .17913 22.756 8.22)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iauYtHb" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 11.441 -1.978)scale(2.50297 1.83731)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="igJtKiW" cx="0" cy="0" r="1" gradientTransform="matrix(.59547 1.06227 -2.45973 1.37884 17.644 1.244)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="isZqhIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.95139 0 0 -.72424 18.671 3.248)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iRsY8od" cx="0" cy="0" r="1" gradientTransform="matrix(2.85308 -4.51731 5.00472 3.16092 13.632 6.743)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="imMm1ib" cx="0" cy="0" r="1" gradientTransform="matrix(2.37481 -2.2626 4.14226 4.34767 20.781 6.629)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iRiyrZb" cx="0" cy="0" r="1" gradientTransform="matrix(2.87968 .3366 -.14093 1.20567 19.997 5.32)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iPALKZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71927 -1.14408 0 20.38 8.81)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iiBUVTc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.265 -.499)scale(.33537 .46172)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIhaQib" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7193 -1.14414 0 16.512 8.81)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iDQ2SXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00686 -.43803 .52653 -.00824 16.258 9.005)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixZLQVQ" cx="0" cy="0" r="1" gradientTransform="matrix(.55724 1.98876 -1.89744 .53165 22.54 8.823)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iNOIMad" cx="0" cy="0" r="1" gradientTransform="matrix(.6984 -.95844 .80337 .5854 22.86 9.306)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iyJRh0d" cx="0" cy="0" r="1" gradientTransform="matrix(.5204 -1.37452 1.83655 .69533 22.96 9.459)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="inKr5Cb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47011 0 0 -1.64159 14.088 9.391)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iuZc0Hc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 .13945 -.14298 -.83307 14.09 9.394)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="iYvXCsb" width="16.1" height="17.295" x="7.545" y="12.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737772 0 0 0 0 0.308243 0 0 0 0 0.219096 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4524"/></filter><filter id="iJk6L0b" width="15.69" height="15.109" x="7.228" y="14.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".5"/></filter><filter id="iMjHsab" width="16.543" height="14.071" x="6.157" y="15.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.290196 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4524"/></filter><filter id="idt55Fs" width="4.451" height="5.283" x="18.446" y="15.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.262745 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4524"/></filter><filter id="i7wHkxd" width="1.542" height=".3" x="6.796" y="26.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".05"/></filter><filter id="ix6OApb" width="1.542" height=".3" x="6.429" y="27.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".05"/></filter><filter id="iZJBZ3c" width="1.542" height=".3" x="6.617" y="28.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".05"/></filter><filter id="iTSSaJc" width="10.061" height="11.141" x="13.957" y="4.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4524"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_4524" result="effect2_innerShadow_13929_4524"/></filter><filter id="isgsKed" width="3.549" height="4.571" x="16.546" y="7.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".5"/></filter><filter id="i21MWKv" width="2.064" height="2.971" x="17.414" y="8.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".1"/></filter><filter id="iqaGWMd" width="3.353" height="1.451" x="16.77" y="11.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".05"/></filter><filter id="iMzQS2U" width="11.412" height="7.465" x="12.74" y="1.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4524"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_4524" result="effect2_innerShadow_13929_4524"/></filter><filter id="iYYe1db" width="2.085" height="1.078" x="19.855" y="6.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4524"/></filter><filter id="iAGCPGe" width="2.085" height="1.065" x="15.195" y="6.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4524"/></filter><filter id="i8x8xvb" width="5.894" height="5.369" x="13.027" y="2.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4524"/><feGaussianBlur result="effect2_foregroundBlur_13929_4524" stdDeviation=".125"/></filter><filter id="iyss4yd" width="5.627" height="5.085" x="18.309" y="2.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".125"/></filter><filter id="iBUWONc" width=".72" height=".64" x="19.719" y="8.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".05"/></filter><filter id="iQMwdBf" width=".836" height=".855" x="20.452" y="8.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".1"/></filter><filter id="ia8xZZC" width=".92" height=".967" x="16.513" y="8.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".1"/></filter><filter id="i0Oezgc" width=".832" height=".647" x="15.855" y="8.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".05"/></filter><filter id="iPCmdme" width="1.235" height="2.166" x="13.027" y="8.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".125"/></filter><filter id="iKSUQEc" width="1.839" height="2.688" x="22.329" y="8.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".25"/></filter><filter id="iKZS7Bc" width="2.117" height="1.014" x="15.131" y="6.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".1"/></filter><filter id="iA9o6VN" width="2.067" height=".964" x="19.836" y="6.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".1"/></filter><filter id="ig7ftkH" width="4.839" height="2.834" x="19.141" y="2.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".375"/></filter><filter id="iwrlyHc" width="12.538" height="9.787" x="8.325" y="19.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4524" stdDeviation=".4"/></filter><linearGradient id="iiqUFBe" x1="20.071" x2="7.415" y1="20.805" y2="30.586" gradientUnits="userSpaceOnUse"><stop class="vdkh2zb2x"/><stop offset="1" class="qa1_iibob"/></linearGradient><linearGradient id="iYAIflb" x1="6.415" x2="9.04" y1="27.68" y2="27.492" gradientUnits="userSpaceOnUse"><stop class="bpl8gqbqy"/><stop offset="1" class="n3pu93i9n"/></linearGradient><linearGradient id="iO434le" x1="19.727" x2="18.79" y1="18.711" y2="20.524" gradientUnits="userSpaceOnUse"><stop class="xsjyr3krk"/><stop offset="1" class="ojhsktbec"/></linearGradient><linearGradient id="iYyQBod" x1="6.946" x2="8.399" y1="26.571" y2="26.571" gradientUnits="userSpaceOnUse"><stop class="m6_nucbsf"/><stop offset="1" class="rbqd_cczp"/></linearGradient><linearGradient id="iLUOnPH" x1="6.579" x2="8.032" y1="27.508" y2="27.508" gradientUnits="userSpaceOnUse"><stop class="m6_nucbsf"/><stop offset="1" class="rbqd_cczp"/></linearGradient><linearGradient id="iOKMflT" x1="6.767" x2="8.22" y1="28.407" y2="28.407" gradientUnits="userSpaceOnUse"><stop class="m6_nucbsf"/><stop offset="1" class="rbqd_cczp"/></linearGradient><linearGradient id="iHrTIcK" x1="23.018" x2="20.776" y1="11.117" y2="11.117" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="i2O41Ic" x1="19.189" x2="18.446" y1="10.221" y2="10.252" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iIfJdBc" x1="18.446" x2="18.446" y1="11.231" y2="10.819" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iGYAAic" x1="18.446" x2="18.446" y1="8.833" y2="9.318" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="i9trg6c" x1="18.815" x2="18.815" y1="11.354" y2="11.183" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="iksgqDd" x1="17.381" x2="17.663" y1="12.624" y2="11.884" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="ihKCVPb" x1="24.521" x2="14.226" y1="4.603" y2="4.603" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="ir0l5Be" x1="21.07" x2="20.792" y1="8.858" y2="9.03" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJu8wLt" x1="17.172" x2="16.893" y1="8.858" y2="9.03" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwz230b" x1="24.152" x2="23.082" y1="8.882" y2="10.812" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="ihbGPec" x1="13.26" x2="14.553" y1="9.506" y2="9.393" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="i6TCppd" x1="23.248" x2="23.248" y1="8.544" y2="10.231" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="isJkioe" x1="19.969" x2="6.781" y1="20.625" y2="29.156" gradientUnits="userSpaceOnUse"><stop class="powb9hb_w"/><stop offset="1" class="ji1uvxbkw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pregnant-person-medium-dark" /></template>
<style>
.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.a6zzhdb-b {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M15.423 6.885a2.46 2.46 0 0 1 1.542-.319a.246.246 0 1 1-.06.488a1.97 1.97 0 0 0-1.23.253l-.081.053l-.003.002a.246.246 0 0 1-.3-.39z");
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.acwz0eb8o {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m18.653 4.645l-.06-.122a.59.59 0 0 0-.545-.37H16.92c-1.636 0-2.962 1.34-2.962 2.995v.244c-.302-.23-.68-.713-.68-1.496c0-.95.692-1.43 1.134-1.737c.125-.087.23-.16.293-.225l.089-.093c.31-.328.862-.914 1.826-1.17a4.8 4.8 0 0 1 1.244-.147c.473.003.807.411.807.884v1.225z");
}

.afzezoczn {
  d: path("M16.856 12.5c-2.205.676-3.886 3.248-3.886 5.61v.717c0 .24-.173.446-.407.503c-2.869.706-5.018 3.107-5.018 6.149v1.215c0 1.657 1.345 3 3.004 3l10.163.012c.968 0 1.684-.784 1.684-1.75V15.722c0-1.295-.846-2.238-2.038-2.487q-.231-.047-.462-.098a3.5 3.5 0 0 1-.763-.257l-.059-.029c-.694-.346-1.476-.578-2.218-.35");
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.akwhn1mys {
  stop-color: var(--svg-color--ee3404, #EE3404);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b0o7qyb_k {
  d: path("M13.938 8.56a.847.847 0 0 0 .074 1.667q-.047-.833-.074-1.666");
}

.ba0qpdb6z {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.325 8.555c.056.075-.062.167-.196.268c-.134.1-.233.17-.29.095s.007-.218.14-.318c.135-.1.29-.12.346-.045");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bln9d_bpn {
  d: path("M20.325 8.555c.056.075-.062.167-.196.268c-.134.1-.233.17-.29.095s.007-.218.14-.318c.135-.1.29-.12.346-.045");
}

.bpl8gqbqy {
  stop-color: var(--svg-color--806059, #806059);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c8y-ucoim {
  cx: 16.271px;
  cy: 8.726px;
  rx: 0.345px;
  ry: 0.175px;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dskl7d_tu {
  d: path("M16.51 8.388a.79.79 0 0 0-.763 1h1.53a.797.797 0 0 0-.766-1");
}

.dsv_opieh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M6.58 27.508h1.24");
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

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.eb1a7s11t {
  d: path("M22.81 10.812q.088-1.415.164-2.83a1.427 1.427 0 0 1-.164 2.83");
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

.f0ohsabjz {
  d: path("m18.107 8.99l-.47 1.63c-.097.335.134.67.46.67h.698c.327 0 .558-.34.461-.67l-.47-1.63c-.102-.362-.573-.362-.679 0");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdpsqp4nn {
  d: path("m23.068 7.54l-.026-.56c-.01-.676-.57-1.235-1.246-1.263h-1.241c-.788 0-1.507-.43-1.883-1.117c0 0-.021-.048-.05-.135c-.316-.952.625-1.701 1.6-1.466c.784.19 1.638.487 2.302.92c1.547 1.008 1.358 2.765.543 3.621");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fygum0ndx {
  d: path("M22.665 18.082c.39-1.09-.127-2.166-.976-2.533a1.675 1.675 0 0 0-2.202.872c-.266.616-.533 1.241-1.04 2.228l3.046 1.945c.567-1.098.924-1.82 1.172-2.512");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h-d21x52g {
  stop-color: var(--svg-color--ec541d, #EC541D);
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h99bv8gma {
  fill: var(--svg-color--000, #000);
  d: path("M16.963 9.18a.45.45 0 0 0-.453-.454a.45.45 0 0 0-.403.662h.802a.45.45 0 0 0 .054-.209");
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

.i0nsp7bni {
  stop-color: var(--svg-color--d7454a, #D7454A);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iagna2bvo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M6.946 26.57h1.242");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.imi34--zw {
  stop-color: var(--svg-color--ff7634, #FF7634);
  stop-opacity: 0;
}

.j0n9-bc_s {
  stop-color: var(--svg-color--ff7a45, #FF7A45);
  stop-opacity: 0;
}

.j9mdirbao {
  stop-color: var(--svg-color--fc5428, #FC5428);
  stop-opacity: 0;
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.ji1uvxbkw {
  stop-color: var(--svg-color--8c6161, #8C6161);
  stop-opacity: 0;
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k-5y-nbih {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m18.107 8.99l-.47 1.63c-.097.335.134.67.46.67h.698c.327 0 .558-.34.461-.67l-.47-1.63c-.102-.362-.573-.362-.679 0");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k7mpzkb9f {
  cx: 16.271px;
  cy: 8.726px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.345px;
  ry: 0.175px;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l863e7bwo {
  stop-color: var(--svg-color--ff6420, #FF6420);
}

.le_3nbbjw {
  stop-color: var(--svg-color--ff7634, #FF7634);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llbkdob_q {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.603 7.092a2.05 2.05 0 0 0-1.467-.338");
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lv92e9blh {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M22.164 4.605h-1.845a.428.428 0 1 1 .068-.852c.479.076 1.114.182 1.54.288c.962.239 1.228.707 1.302 1.041a1.34 1.34 0 0 0-1.065-.477");
}

.lyglqcbey {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m23.068 7.54l-.026-.56c-.01-.676-.57-1.235-1.246-1.263h-1.241c-.788 0-1.507-.43-1.883-1.117c0 0-.021-.048-.05-.135c-.316-.952.625-1.701 1.6-1.466c.784.19 1.638.487 2.302.92c1.547 1.008 1.358 2.765.543 3.621");
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m2co8ibdp {
  d: path("M18.446 12.191c-.45 0-.873-.106-1.228-.291c-.121-.062-.252.075-.175.185c.297.45.814.75 1.403.75s1.107-.3 1.404-.75c.076-.114-.054-.247-.175-.185a2.65 2.65 0 0 1-1.229.291");
}

.m56ub07gi {
  d: path("M21.69 15.549a1.676 1.676 0 0 1 .872 2.202c-.383.886-1.065 2.411-1.961 3.979c-.879 1.537-2.043 3.259-3.434 4.433c-2.342 1.976-4.764 2.698-6.745 2.923c-.929.129-2.169.232-3.109.184c-.457-.024-.735-.232-.785-.477a.5.5 0 0 1 .062-.366a.526.526 0 0 1-.177-.9a.525.525 0 0 1 .27-.976h.18a.504.504 0 0 1 .243-.945h1.098a1.6 1.6 0 0 1-.258-.43c-.1-.237.024-.507.253-.623c.237-.12.522-.04.692.164c.598.713 1.248 1.044 1.79.947c1.352-.24 2.917-.805 4.351-2.015c.935-.79 1.84-2.144 2.66-3.581c.804-1.407 1.428-2.799 1.795-3.647a1.675 1.675 0 0 1 2.202-.872");
}

.m6_nucbsf {
  stop-color: var(--svg-color--6a4a3f, #6A4A3F);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mnryjhdzq {
  fill: var(--svg-color--000, #000);
  d: path("M19.93 9.18a.45.45 0 0 1 .453-.454a.45.45 0 0 1 .403.662h-.802a.4.4 0 0 1-.054-.209");
}

.mrc1www1l {
  d: path("m18.653 4.645l-.06-.122a.59.59 0 0 0-.545-.37H16.92c-1.636 0-2.962 1.34-2.962 2.995v.244c-.302-.23-.68-.713-.68-1.496c0-.95.692-1.43 1.134-1.737c.125-.087.23-.16.293-.225l.089-.093c.31-.328.862-.914 1.826-1.17a4.8 4.8 0 0 1 1.244-.147c.473.003.807.411.807.884v1.225z");
}

.mtd419brd {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.253 11.834c.344.179.755.282 1.193.282c.443 0 .85-.103 1.194-.282a.21.21 0 0 1 .25.04a.2.2 0 0 1 .023.253m-2.66-.293l2.597.251m-2.597-.252h-.001a.21.21 0 0 0-.25.043a.196.196 0 0 0-.022.251m.273-.293l-.21.251m2.87.042l-.063-.042m.063.042l-.063-.042m.063.042c-.31.47-.851.783-1.467.783a1.75 1.75 0 0 1-1.466-.783m2.87-.042c-.297.45-.814.75-1.404.75s-1.107-.3-1.403-.75m-.063.042l.001.001l.062-.043m-.063.042l.063-.042");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n3pu93i9n {
  stop-color: var(--svg-color--73514e, #73514E);
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

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.o8g716qws {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m18.09 9.163l-.523 1.63c-.09.335.125.67.43.67h.648c.304 0 .519-.34.43-.67l-.439-1.63c-.094-.361-.447-.361-.545 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojhsktbec {
  stop-color: var(--svg-color--6d4a46, #6D4A46);
  stop-opacity: 0;
}

.olsg4hb9z {
  fill: var(--svg-color--ff6428, #FF6428);
  d: path("M16.856 12.5c-2.205.676-3.886 3.248-3.886 5.61v.717c0 .24-.173.446-.407.503c-2.869.706-5.018 3.107-5.018 6.149v1.215c0 1.657 1.345 3 3.004 3l10.163.012c.968 0 1.684-.784 1.684-1.75V15.722c0-1.295-.846-2.238-2.038-2.487q-.231-.047-.462-.098a3.5 3.5 0 0 1-.763-.257l-.059-.029c-.694-.346-1.476-.578-2.218-.35");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p5xnx_9wf {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.456 7.133a2.05 2.05 0 0 1 1.467-.338");
}

.pdfzhccus {
  d: path("M21.087 9.075a.75.75 0 0 0-.205-.41l-.23.252l.104.203z");
}

.phlxv6bym {
  stop-color: var(--svg-color--ff5d1d, #FF5D1D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.powb9hb_w {
  stop-color: var(--svg-color--8c6161, #8C6161);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q4wz22bch {
  stroke-linecap: round;
  d: path("M19.563 20.375c-1.042 2.063-4.488 6.387-9.938 7.188");
}

.qa1_iibob {
  stop-color: var(--svg-color--845b5b, #845B5B);
}

.qd9b8r05y {
  d: path("M14.137 10.731a1.45 1.45 0 0 1-.802-.274v.826c0 .792.471 1.497 1.188 1.79a3.6 3.6 0 0 1-.306-1.046z");
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

.r2yxhcjfl {
  d: path("M14.169 12.074a3.47 3.47 0 0 0 3.445 3.02h1.672a3.47 3.47 0 0 0 3.445-3.02c.105-1.67.21-3.333.287-5.002a1.285 1.285 0 0 0-1.222-1.27h-1.241a2.15 2.15 0 0 1-1.961-1.279a.59.59 0 0 0-.546-.37H16.92c-1.637 0-2.963 1.34-2.963 2.995c0 1.65.104 3.273.212 4.926");
}

.rbqd_cczp {
  stop-color: var(--svg-color--6a4a3f, #6A4A3F);
  stop-opacity: 0;
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s6g7h-5ni {
  d: path("M22.829 10.231q.051-.843.098-1.687a.847.847 0 0 1-.098 1.687");
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

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.v1lpopbju {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.566 8.147c.58 0 1.068.4 1.201.939a.243.243 0 0 1-.237.302h-1.978a.204.204 0 0 1-.201-.241c.111-.568.61-1 1.215-1");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vdkh2zb2x {
  stop-color: var(--svg-color--825c5d, #825C5D);
}

.vitxoz2-x {
  fill: var(--svg-color--e23405, #E23405);
  d: path("M10.47 28.739q.229-.029.44-.06c1.886-.224 3.507-.32 5.738-2.297c1.325-1.174 2.434-2.896 3.27-4.433c.854-1.568 1.503-3.093 1.868-3.98c.35-.848-.022-1.834-.83-2.202c-.81-.367-1.749.024-2.098.873c-.35.848-.944 2.24-1.71 3.646c-.782 1.437-1.644 2.792-2.534 3.581a8.56 8.56 0 0 1-4.145 2.016c-.516.096-1.135-.235-1.704-.947a.56.56 0 0 0-.494-.216a7 7 0 0 0-.043.759v1.215c0 1.163 1.318 1.547 2.241 2.045");
}

.vkgfzqx5q {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M21.756 6.981a1.6 1.6 0 0 0-.61-.364c-.27-.085-.607-.108-1.075-.05a.246.246 0 1 0 .06.487c.427-.052.688-.025.867.032c.176.055.295.145.435.266a.246.246 0 0 0 .323-.37");
}

.vp7op3b3o {
  stop-color: var(--svg-color--ee3404, #EE3404);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x2wzb6b0f {
  d: path("M20.383 8.388a.79.79 0 0 1 .762 1h-1.528a.794.794 0 0 1 .766-1");
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xhl3qijdh {
  stop-color: var(--svg-color--ff8147, #FF8147);
}

.xhwuyccef {
  d: path("M22.75 3.734c.456.157.866.475 1.124.932a2.1 2.1 0 0 1-.094 2.24c-.155.228-.24.499-.24.774v1.054a1.55 1.55 0 0 0-.591-.238l.07-1.424a1.285 1.285 0 0 0-1.223-1.27h-1.241c-.847 0-1.613-.5-1.961-1.279a.59.59 0 0 0-.546-.37H16.92c-1.637 0-2.962 1.34-2.962 2.995l.027 1.363c-.225.033-.46.108-.639.233V7.68a1.4 1.4 0 0 0-.24-.775a2.12 2.12 0 0 1-.127-2.168c.26-.49.678-.832 1.153-.999c.507-.18.94-.523 1.227-.984a2.06 2.06 0 0 1 2.562-.808c.339.147.72.147 1.058 0c.25-.105.522-.167.81-.167c.747 0 1.4.404 1.762 1.004c.273.451.701.78 1.2.95");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xsjyr3krk {
  stop-color: var(--svg-color--6d4a46, #6D4A46);
}

.y3-5caior {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.327 8.147c-.58 0-1.068.4-1.201.939a.243.243 0 0 0 .237.302h1.978a.204.204 0 0 0 .201-.241c-.111-.568-.615-1-1.215-1");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.y8skcxtgz {
  stop-color: var(--svg-color--ff7a45, #FF7A45);
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zmvga4bhq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M6.767 28.407h1.242");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zvu5-bczw {
  d: path("M17.233 9.086c0-.256-.208-.426-.264-.478l-.256.248l.158.32z");
}

.zx-2c3btz {
  d: path("M13.974 7.97a1.44 1.44 0 0 0-1.234 1.417c0 .762.597 1.384 1.348 1.425a69 69 0 0 1-.114-2.841");
}

.zzd-j_97z {
  d: path("M22.756 10.731c.297-.01.576-.11.802-.274v.826c0 .792-.472 1.497-1.189 1.79q.228-.484.307-1.046z");
}

</style>
