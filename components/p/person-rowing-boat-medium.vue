<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEkZDtd)" transform="rotate(39.16 14.713 7.843)" class="ika1-2y1s"/><path fill="url(#iUpfnbb)" class="db46b5bpu"/><g filter="url(#i5HYWbe)"><path fill="url(#i5LnNue)" class="haow5v_7u"/><path fill="url(#iBDjfDc)" class="haow5v_7u"/><path fill="url(#itbIKic)" class="haow5v_7u"/></g><path clip-rule="evenodd" class="u6t07yb6x"/><g filter="url(#irue0Oy)"><path clip-rule="evenodd" class="vl6r-pbea"/></g><g filter="url(#ibkAgjb)"><path fill="url(#ihxCCVb)" class="bqkhiubvn"/><path fill="url(#iMiJPfe)" class="bqkhiubvn"/></g><path fill="url(#iOWToQe)" class="juxqywwgb"/><g filter="url(#iJidLib)"><path class="xxm4ecbgb"/><path fill="url(#imGHS6b)" class="l6izdhbaq"/></g><path fill="url(#ifKdFpb)" class="hec337bhq"/><path fill="url(#iOY3nSd)" class="byj_tusbv"/><path fill="url(#i7Z3auf)" class="byj_tusbv"/><path fill="url(#ir7mOzb)" class="byj_tusbv"/><path fill="url(#idcv5MZ)" class="byj_tusbv"/><g filter="url(#ih7N2pe)"><path fill="url(#iUVFBcJ)" class="xd_oaursx"/><path fill="url(#iDzhVjH)" class="xd_oaursx"/><path fill="url(#i0ioFLd)" class="xd_oaursx"/></g><g filter="url(#iDGE5ud)"><rect fill="url(#ibeqGmc)" class="xi79cqbov"/><rect fill="url(#i5jKrPK)" class="xi79cqbov"/><rect fill="url(#ia7G8VW)" class="xi79cqbov"/><rect fill="url(#iqg8wwe)" class="xi79cqbov"/></g><rect fill="url(#is4e2tc)" transform="rotate(-21.787 19.523 13.2)" class="ldmnoc93z"/><path fill="url(#iejlYNR)" class="aezesdoxk"/><path fill="url(#i0r1ukd)" class="aezesdoxk"/><path fill="url(#iPXB77c)" class="aezesdoxk"/><g filter="url(#iVm7BWd)"><path fill="url(#im3ByDd)" class="w9i0dw05x"/></g><g filter="url(#ipJQbxd)"><path fill="url(#iwBGalc)" class="l38fjjxxv"/><path fill="url(#irMrJZd)" class="l38fjjxxv"/><path fill="url(#ikMi4Ej)" class="l38fjjxxv"/></g><g filter="url(#ib6Q9FB)"><path class="rqnevkbic"/><path fill="url(#iocGlXT)" class="sim5a-buc"/></g><g filter="url(#iOjlmGW)"><path stroke="url(#iAwjdub)" class="qh82v_bsc"/></g><g filter="url(#iivW0Ac)"><path fill="url(#iE46RMb)" class="g4h37tb4v"/></g><path class="xf_0o3b5u"/><path fill="url(#iYECTTf)" class="k1t8vd3qj"/><path fill="url(#i8PjAJe)" class="zaw99mhln"/><path class="crt8g8flt"/><g filter="url(#i3QO3Ke)"><path class="wsms_nb_h"/></g><defs><radialGradient id="iEkZDtd" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.27 9.725)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="bbppnek8h"/><stop offset="1" class="wj36x1bhr"/></radialGradient><radialGradient id="iUpfnbb" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.213 10.59)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="i531rrbeb"/><stop offset="1" class="zto3p_lef"/></radialGradient><radialGradient id="i5LnNue" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.161 5.347)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="gyymo5b9p"/><stop offset="1" class="ikvhpob1k"/></radialGradient><radialGradient id="iBDjfDc" cx="0" cy="0" r="1" gradientTransform="rotate(107.289 5.82 10.255)scale(.61776 .64399)" gradientUnits="userSpaceOnUse"><stop class="v5j-79bqk"/><stop offset="1" class="r5lh8e62q"/></radialGradient><radialGradient id="itbIKic" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.237)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="uee_89odc"/><stop offset="1" class="g491cdewz"/></radialGradient><radialGradient id="ihxCCVb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 1.21872 -1.51845 -5.21735 18.363 5.82)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="pb023zb_t"/><stop offset="1" class="t-gnmrvnp"/></radialGradient><radialGradient id="iMiJPfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.53125 1.3125 0 14.685 7.175)" gradientUnits="userSpaceOnUse"><stop class="baj5svbcv"/><stop offset="1" class="od3gao5lw"/></radialGradient><radialGradient id="iOWToQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -.1328 .22485 -.63488 15.855 7.07)" gradientUnits="userSpaceOnUse"><stop class="arf1s8bxe"/><stop offset="1" class="zyktje01y"/></radialGradient><radialGradient id="imGHS6b" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.142 15.31)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="cpjrx4bdc"/><stop offset="1" class="gezrebbgs"/></radialGradient><radialGradient id="ifKdFpb" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.644 48.723)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="ir7mOzb" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 22.164)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="idcv5MZ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 22.07)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iUVFBcJ" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.19 15.16)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="iDzhVjH" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.922 10.475)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="i0ioFLd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.257)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="i5jKrPK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.289)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="ia7G8VW" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.76)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="iqg8wwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.957 16.539)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="is4e2tc" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 20.018 13.461)" gradientUnits="userSpaceOnUse"><stop class="yj2immbwm"/><stop offset="1" class="g-0n7qbjd"/></radialGradient><radialGradient id="iejlYNR" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.285 10.84)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="im3ByDd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 21.101)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="irMrJZd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 29.07)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iocGlXT" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29688 .16254 .33364 20.747 14.05)" gradientUnits="userSpaceOnUse"><stop class="roxpyebqa"/><stop offset="1" class="xi66vkmon"/></radialGradient><radialGradient id="iE46RMb" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.289)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="r_erdlb4g"/><stop offset="1" class="w1kjbmbah"/></radialGradient><radialGradient id="iYECTTf" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 17.543 7.898)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="i8PjAJe" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.632)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><filter id="i5HYWbe" width="4.364" height="4.439" x="14.22" y="5.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.317647 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23070"/></filter><filter id="irue0Oy" width=".763" height=".367" x="17.245" y="6.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23070"/></filter><filter id="ibkAgjb" width="5.022" height="4.224" x="13.841" y="4.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0901961 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23070"/></filter><filter id="iJidLib" width="6.377" height="6.141" x="9.574" y="9.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.478431 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23070"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.466667 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23070" result="effect2_innerShadow_3987_23070"/></filter><filter id="ih7N2pe" width="27.983" height="6.037" x="2.059" y="20.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23070"/></filter><filter id="iDGE5ud" width="24.059" height="2.191" x="3.886" y="15.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23070"/></filter><filter id="iVm7BWd" width="6.802" height="6.803" x="8.337" y="19.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23070"/></filter><filter id="ipJQbxd" width="27.983" height="6.037" x="1.959" y="24.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23070"/></filter><filter id="ib6Q9FB" width="6.678" height="4.108" x="14.785" y="10.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.419608 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23070"/></filter><filter id="iOjlmGW" width="5.181" height="3.008" x="14.85" y="11.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23070" stdDeviation=".2"/></filter><filter id="iivW0Ac" width="3.882" height="3.705" x="12.803" y="9.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.25098 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23070"/></filter><filter id="i3QO3Ke" width="3.316" height="1.688" x="15.443" y="5.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23070" stdDeviation=".125"/></filter><linearGradient id="iOY3nSd" x1="25.051" x2="7.801" y1="19.007" y2="24.382" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="i7Z3auf" x1="27.145" x2="26.441" y1="20.57" y2="20.57" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="ibeqGmc" x1="16.015" x2="16.395" y1="15.414" y2="18.945" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="i0r1ukd" x1="17.168" x2="17.582" y1="16.449" y2="16.843" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="iPXB77c" x1="19.52" x2="19.184" y1="16.132" y2="15.781" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="iwBGalc" x1="18.457" x2="12.738" y1="23.539" y2="33.632" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="ikMi4Ej" x1="18.02" x2="18.02" y1="30.101" y2="29.82" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="iAwjdub" x1="15.778" x2="20.06" y1="12.393" y2="14.112" gradientUnits="userSpaceOnUse"><stop class="lhom_fbjg"/><stop offset="1" class="s09h4qbjb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-rowing-boat-medium" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.aezesdoxk {
  d: path("M21.334 12.416a.59.59 0 0 1 .829.84l-8.439 8.33a.59.59 0 1 1-.829-.838z");
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.arf1s8bxe {
  stop-color: var(--svg-color--b69281, #B69281);
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.baj5svbcv {
  stop-color: var(--svg-color--4f3f3c, #4F3F3C);
}

.bbppnek8h {
  stop-color: var(--svg-color--8c4f4f, #8C4F4F);
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.bqkhiubvn {
  d: path("M13.872 7.704c.085-.194.296-.226.39-.219c-.39-.765-.085-2.687.65-3.046a1.77 1.77 0 0 1 1.577.023c.243.133.567.445 1.27.41c.645-.032 1 .332 1.004.692s-.117.843-.637.96c-.52.118-.758-.07-1.394-.148c-.492-.06-.866.277-.989.469c-.183.29-.615.915-.75 1.137c-.168.277-.406.402-.73.34c-.324-.063-.496-.376-.39-.618");
}

.byj_tusbv {
  d: path("m5.232 17.123l21.725-.022v6.25l-18.008-.117z");
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.cpjrx4bdc {
  stop-color: var(--svg-color--e03932, #E03932);
}

.crt8g8flt {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.548c.016-.037.07-.049.119-.027s.075.07.059.107c-.017.036-.07.048-.119.026s-.075-.07-.059-.106");
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.db46b5bpu {
  d: path("M18.232 8.199c-.081-.147-.066-.412-.047-.504l-.445 1.02c.14.074.378.139.515-.032c.098-.12.079-.3-.023-.484");
}

.dzuixsuao {
  stop-color: var(--svg-color--55beff, #55BEFF);
  stop-opacity: 0;
}

.e_s-6on8g {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
  stop-opacity: 0;
}

.e21-2rm4b {
  stop-color: var(--svg-color--659941, #659941);
}

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
}

.f3ogmdbgo {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
}

.f6scwccnd {
  stop-color: var(--svg-color--4d8c4e, #4D8C4E);
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-0n7qbjd {
  stop-color: var(--svg-color--a28169, #A28169);
}

.g491cdewz {
  stop-color: var(--svg-color--b68e7e, #B68E7E);
  stop-opacity: 0;
}

.g4h37tb4v {
  d: path("M13.004 11.21c.6.72 1.333 1.555 1.625 1.883l1.656-1.484c-.33-.396-1.117-1.303-1.617-1.766c-.625-.578-1.27-.191-1.469 0c-.172.166-.672.688-.195 1.368");
}

.gezrebbgs {
  stop-color: var(--svg-color--e03932, #E03932);
  stop-opacity: 0;
}

.gyymo5b9p {
  stop-color: var(--svg-color--bc907a, #BC907A);
}

.haow5v_7u {
  d: path("M15.931 9.804c-.914-.453-1.535-1.235-1.71-1.617l.662-1.593a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.003.372.066c.288.183.576.645.369 1.476c-.229 1.08-.501 1.744-.749 2.227c-.177.344-.533.572-.916.505a3 3 0 0 1-.718-.216");
}

.hec337bhq {
  d: path("M9.598 13.867c-.243.894-.203 1.761-.11 2.023l6.309-.062z");
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.i531rrbeb {
  stop-color: var(--svg-color--bf937d, #BF937D);
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ika1-2y1s {
  d: path("M14.713 7.843h1.744v2h-1.744z");
}

.ikvhpob1k {
  stop-color: var(--svg-color--ae7d72, #AE7D72);
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.juxqywwgb {
  d: path("M15.919 6.713a.625.625 0 0 0-.373 1.175z");
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k1t8vd3qj {
  d: path("M17.72 7.94c.02-.036.038-.063.051-.112c.048-.178-.02-.355-.169-.395c-.138-.037-.296.08-.343.257a.5.5 0 0 0-.012.124z");
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.l38fjjxxv {
  d: path("M3.504 24.586c-.775-.425-1.254-.422-1.445-.422V30.1H29.94v-5.937c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.102-1.539-.438c-.703-.335-1.324-.703-1.98-.703c-.654 0-1.311.334-1.88.622l-.007.003c-.57.29-1.031.516-1.656.516s-1.031-.203-2-.734");
}

.l6izdhbaq {
  d: path("M11.168 10.71c-1.006 1.232-1.414 2.669-1.594 3.274l3.992 1.25c.125-1.023.75-2.719 1.172-3.375s.489-.871.555-1.348c.066-.476-.256-1.194-1.336-1.394c-.844-.156-1.854.45-2.789 1.594");
}

.ldmnoc93z {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 13.201px;
  rx: 0.318px;
}

.lhom_fbjg {
  stop-color: var(--svg-color--ba9080, #BA9080);
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.od3gao5lw {
  stop-color: var(--svg-color--4f3f3c, #4F3F3C);
  stop-opacity: 0;
}

.pb023zb_t {
  stop-color: var(--svg-color--5e413e, #5E413E);
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.qh82v_bsc {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.403 11.862c.292.35.89.87 1.805 1.164c1.438.461 1.734.516 2.36.727");
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.r_erdlb4g {
  stop-color: var(--svg-color--ff9954, #FF9954);
}

.r5lh8e62q {
  stop-color: var(--svg-color--c9a289, #C9A289);
  stop-opacity: 0;
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.roxpyebqa {
  stop-color: var(--svg-color--c59e89, #C59E89);
}

.rqnevkbic {
  fill: var(--svg-color--b59073, #B59073);
  d: path("M16.504 13.922c-.713-.332-1.443-.967-1.719-1.243l1.281-1.191c1.157 1.11 2.375 1.278 2.684 1.351c.395.094 1.538.301 2.168.73c.516.352.379.993.07 1.267c-.254.224-.675.335-1.011.203c-.336-.133-.559-.27-1.227-.399a10 10 0 0 1-2.246-.719");
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.s09h4qbjb {
  stop-color: var(--svg-color--ba9080, #BA9080);
  stop-opacity: 0;
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.sim5a-buc {
  d: path("M16.504 13.922c-.713-.332-1.443-.967-1.719-1.243l1.281-1.191c1.157 1.11 2.375 1.278 2.684 1.351c.395.094 1.538.301 2.168.73c.516.352.379.993.07 1.267c-.254.224-.675.335-1.011.203c-.336-.133-.559-.27-1.227-.399a10 10 0 0 1-2.246-.719");
}

.t-gnmrvnp {
  stop-color: var(--svg-color--422b32, #422B32);
}

.u6t07yb6x {
  fill: var(--svg-color--880f4d, #880F4D);
  fill-rule: evenodd;
  d: path("M16.98 8.608a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.184a.92.92 0 0 1-.442-.426a.1.1 0 0 1 .05-.132");
}

.uee_89odc {
  stop-color: var(--svg-color--b68e7e, #B68E7E);
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5j-79bqk {
  stop-color: var(--svg-color--c9a289, #C9A289);
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.vl6r-pbea {
  fill: var(--svg-color--594343, #594343);
  fill-rule: evenodd;
  d: path("M17.866 7.087a.72.72 0 0 0-.488-.028a.1.1 0 0 1-.066-.189a.92.92 0 0 1 .637.035a.1.1 0 1 1-.083.182");
}

.w1kjbmbah {
  stop-color: var(--svg-color--f9663c, #F9663C);
}

.w9i0dw05x {
  d: path("M11.366 20.465a1.917 1.917 0 0 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 0 1-2.712-2.712z");
}

.wj36x1bhr {
  stop-color: var(--svg-color--9c7060, #9C7060);
}

.wqxg4jbgc {
  stop-color: var(--svg-color--286ec5, #286EC5);
  stop-opacity: 0;
}

.wsms_nb_h {
  fill: var(--svg-color--664b4a, #664B4A);
  d: path("M17.068 6.175c-.675-.138-1.198.187-1.375.367c.632-1 1.43-.656 2.054-.68c.5-.019.709-.346.75-.508c.006.172.064.53-.144.715c-.256.228-.442.278-1.285.106");
}

.wvez-gyvu {
  stop-color: var(--svg-color--86bf45, #86BF45);
}

.wwotuurhh {
  stop-color: var(--svg-color--528c3f, #528C3F);
  stop-opacity: 0;
}

.xd_oaursx {
  d: path("M3.504 21.086c-.775-.425-1.254-.422-1.445-.422V26.6H29.94v-5.937c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.102-1.539-.438c-.703-.335-1.324-.703-1.98-.703c-.654 0-1.311.334-1.88.622l-.007.003c-.57.29-1.031.516-1.656.516s-1.031-.203-2-.734");
}

.xf_0o3b5u {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.92c.048.013.099-.026.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.051-.434.031-.5.277l-.003.01c-.015.06.01.119.066.134z");
}

.xi66vkmon {
  stop-color: var(--svg-color--c59e89, #C59E89);
  stop-opacity: 0;
}

.xi79cqbov {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.664px;
  rx: 1.095px;
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.xxm4ecbgb {
  fill: var(--svg-color--fa623e, #FA623E);
  d: path("M11.168 10.71c-1.006 1.232-1.414 2.669-1.594 3.274l3.992 1.25c.125-1.023.75-2.719 1.172-3.375s.489-.871.555-1.348c.066-.476-.256-1.194-1.336-1.394c-.844-.156-1.854.45-2.789 1.594");
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.yj2immbwm {
  stop-color: var(--svg-color--ac8d79, #AC8D79);
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zaw99mhln {
  d: path("M17.641 7.919q.045-.051.061-.11c.027-.099-.019-.206-.097-.227c-.08-.021-.17.04-.198.147a.3.3 0 0 0-.002.126z");
}

.zto3p_lef {
  stop-color: var(--svg-color--b68375, #B68375);
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

.zyktje01y {
  stop-color: var(--svg-color--a37c6b, #A37C6B);
}

</style>
