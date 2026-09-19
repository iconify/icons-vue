<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iN19g6b)" transform="rotate(39.16 14.713 7.729)" class="k_odxeboz"/><path fill="url(#isQX2Ne)" class="seb5mcv_j"/><g filter="url(#il2GtOd)"><path fill="url(#in2zgls)" class="tc1_y3b9f"/><path fill="url(#ilDUhib)" class="tc1_y3b9f"/><path fill="url(#ixhhIpe)" class="tc1_y3b9f"/></g><path clip-rule="evenodd" class="wj7cv1bow"/><g filter="url(#iar4Nbd)"><path clip-rule="evenodd" class="g0laajs1z"/></g><g filter="url(#iv2Ro9b)"><path fill="url(#iZScP1c)" class="m65xr0s5g"/><path fill="url(#iO9ij1d)" class="m65xr0s5g"/></g><path fill="url(#iQGsS4b)" class="b4uffmbcc"/><g filter="url(#ikWaEue)"><path class="weit5gbyi"/><path fill="url(#iAIb77b)" class="agi_oab-g"/></g><path fill="url(#iA95o2b)" class="pumz-pbhp"/><path fill="url(#inYWo7c)" class="it71nu7tw"/><path fill="url(#ixuQ86b)" class="it71nu7tw"/><path fill="url(#iUp9hae)" class="it71nu7tw"/><path fill="url(#iGJSdof)" class="it71nu7tw"/><g filter="url(#ixnCofh)"><path fill="url(#i6w4PBe)" class="bxdw508so"/><path fill="url(#iuDkKed)" class="bxdw508so"/><path fill="url(#i32s5Ee)" class="bxdw508so"/></g><g filter="url(#iEvHqAc)"><rect fill="url(#iaUpmFe)" class="qs52py0bf"/><rect fill="url(#iumobKd)" class="qs52py0bf"/><rect fill="url(#ipsSFmc)" class="qs52py0bf"/><rect fill="url(#iXQ6jrc)" class="qs52py0bf"/></g><rect fill="url(#icpiIge)" transform="rotate(-21.787 19.523 13.087)" class="qkwj62byu"/><path fill="url(#i68mzMc)" class="dox9w524l"/><path fill="url(#iyoCukb)" class="dox9w524l"/><path fill="url(#imYCnBd)" class="dox9w524l"/><g filter="url(#iCY3uje)"><path fill="url(#i9GqO4d)" class="k8-07jblo"/></g><g filter="url(#iB4zvBQ)"><path fill="url(#itzmh0d)" class="s08zmubju"/><path fill="url(#icS5Hmf)" class="s08zmubju"/><path fill="url(#iQ5zG4d)" class="s08zmubju"/></g><g filter="url(#ilYO9gb)"><path class="a8g-5bbwy"/><path fill="url(#iaB3zob)" class="ka9zhabzx"/></g><g filter="url(#iyZ5wWb)"><path stroke="url(#iaiuisd)" class="x8rdo-2id"/></g><g filter="url(#iBWUrDc)"><path fill="url(#iNw71Xx)" class="a4jtfccge"/></g><path class="jqmxz7bhg"/><path fill="url(#ifbNjZd)" class="wj4eoubdt"/><path fill="url(#iv1qh2d)" class="t8zorw1yi"/><path class="kgie-nbve"/><g filter="url(#im5Nq4s)"><path class="sseixlt9y"/></g><defs><radialGradient id="iN19g6b" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.309 9.668)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="sydryhb-w"/><stop offset="1" class="eb6bfzbys"/></radialGradient><radialGradient id="isQX2Ne" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.254 10.534)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="d983fmb_q"/><stop offset="1" class="ay4s1-bcp"/></radialGradient><radialGradient id="in2zgls" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.17 5.29)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="nvujmsdui"/><stop offset="1" class="cu73xiboa"/></radialGradient><radialGradient id="ilDUhib" cx="0" cy="0" r="1" gradientTransform="rotate(107.289 5.862 10.198)scale(.61776 .64399)" gradientUnits="userSpaceOnUse"><stop class="w_eq7titt"/><stop offset="1" class="s13t8gbqa"/></radialGradient><radialGradient id="ixhhIpe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.123)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="rj26_kbww"/><stop offset="1" class="y6c_odbaq"/></radialGradient><radialGradient id="iZScP1c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 1.21872 -1.51845 -5.21735 18.363 5.706)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="j9b-420yy"/><stop offset="1" class="k5y4d_b1p"/></radialGradient><radialGradient id="iO9ij1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.53125 1.3125 0 14.685 7.06)" gradientUnits="userSpaceOnUse"><stop class="yte4k7nua"/><stop offset="1" class="h846rykft"/></radialGradient><radialGradient id="iQGsS4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -.1328 .22485 -.63488 15.855 6.956)" gradientUnits="userSpaceOnUse"><stop class="k7xyk1boq"/><stop offset="1" class="n3cyb-3sq"/></radialGradient><radialGradient id="iAIb77b" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.065 15.253)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="cpjrx4bdc"/><stop offset="1" class="gezrebbgs"/></radialGradient><radialGradient id="iA95o2b" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.215 48.666)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="iUp9hae" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 22.05)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="iGJSdof" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 21.956)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="i6w4PBe" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.215 15.103)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="iuDkKed" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.897 10.418)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="i32s5Ee" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.144)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="iumobKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.175)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="ipsSFmc" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.646)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="iXQ6jrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.957 16.425)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="icpiIge" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 20.018 13.347)" gradientUnits="userSpaceOnUse"><stop class="bocr3_b9d"/><stop offset="1" class="bzmw0hbwp"/></radialGradient><radialGradient id="i68mzMc" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.308 10.782)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="i9GqO4d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 20.987)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="icS5Hmf" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 28.956)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iaB3zob" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29687 .16254 .33364 20.747 13.935)" gradientUnits="userSpaceOnUse"><stop class="qxt6awing"/><stop offset="1" class="jaxrm4b9t"/></radialGradient><radialGradient id="iNw71Xx" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.175)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="r_erdlb4g"/><stop offset="1" class="w1kjbmbah"/></radialGradient><radialGradient id="ifbNjZd" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 17.543 7.784)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="iv1qh2d" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.52)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><filter id="il2GtOd" width="4.364" height="4.439" x="14.22" y="5.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.196078 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23064"/></filter><filter id="iar4Nbd" width=".763" height=".367" x="17.245" y="6.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.0196078 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23064"/></filter><filter id="iv2Ro9b" width="5.022" height="4.224" x="13.841" y="3.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0588235 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23064"/></filter><filter id="ikWaEue" width="6.377" height="6.141" x="9.574" y="8.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.478431 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23064"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.466667 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23064" result="effect2_innerShadow_3987_23064"/></filter><filter id="ixnCofh" width="27.983" height="6.037" x="2.059" y="20.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23064"/></filter><filter id="iEvHqAc" width="24.059" height="2.191" x="3.886" y="15.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23064"/></filter><filter id="iCY3uje" width="6.802" height="6.803" x="8.337" y="19.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23064"/></filter><filter id="iB4zvBQ" width="27.983" height="6.037" x="1.959" y="24.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23064"/></filter><filter id="ilYO9gb" width="6.678" height="4.108" x="14.785" y="10.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.168627 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23064"/></filter><filter id="iyZ5wWb" width="5.181" height="3.008" x="14.85" y="11.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23064" stdDeviation=".2"/></filter><filter id="iBWUrDc" width="3.882" height="3.705" x="12.803" y="9.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.25098 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23064"/></filter><filter id="im5Nq4s" width="3.316" height="1.688" x="15.443" y="4.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23064" stdDeviation=".125"/></filter><linearGradient id="inYWo7c" x1="25.051" x2="7.801" y1="18.894" y2="24.269" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="ixuQ86b" x1="27.145" x2="26.441" y1="20.456" y2="20.456" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="iaUpmFe" x1="16.015" x2="16.395" y1="15.3" y2="18.831" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="iyoCukb" x1="17.168" x2="17.582" y1="16.335" y2="16.73" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="imYCnBd" x1="19.52" x2="19.184" y1="16.019" y2="15.667" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="itzmh0d" x1="18.457" x2="12.738" y1="23.425" y2="33.519" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="iQ5zG4d" x1="18.02" x2="18.02" y1="29.987" y2="29.706" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="iaiuisd" x1="15.778" x2="20.06" y1="12.28" y2="13.998" gradientUnits="userSpaceOnUse"><stop class="lon_-ybsm"/><stop offset="1" class="i176-27ra"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-rowing-boat-dark" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.a4jtfccge {
  d: path("M13.004 11.097c.6.719 1.333 1.555 1.625 1.883l1.656-1.485c-.33-.396-1.117-1.303-1.617-1.765c-.625-.578-1.27-.192-1.469 0c-.172.165-.672.687-.195 1.367");
}

.a8g-5bbwy {
  fill: var(--svg-color--503633, #503633);
  d: path("M16.504 13.808c-.713-.332-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.278 2.684 1.352c.395.093 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.399a10 10 0 0 1-2.246-.718");
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.agi_oab-g {
  d: path("M11.168 10.597c-1.006 1.231-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.ay4s1-bcp {
  stop-color: var(--svg-color--40292a, #40292A);
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.b4uffmbcc {
  d: path("M15.919 6.599a.625.625 0 0 0-.373 1.175z");
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.bocr3_b9d {
  stop-color: var(--svg-color--5c504d, #5C504D);
}

.bxdw508so {
  d: path("M3.504 20.972c-.775-.425-1.254-.422-1.445-.422v5.937H29.94V20.55c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.bzmw0hbwp {
  stop-color: var(--svg-color--47332f, #47332F);
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.cpjrx4bdc {
  stop-color: var(--svg-color--e03932, #E03932);
}

.cu73xiboa {
  stop-color: var(--svg-color--492d2d, #492D2D);
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.d983fmb_q {
  stop-color: var(--svg-color--5a4644, #5A4644);
}

.dox9w524l {
  d: path("M21.334 12.302a.59.59 0 1 1 .829.84l-8.439 8.331a.59.59 0 0 1-.829-.84z");
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

.eb6bfzbys {
  stop-color: var(--svg-color--453230, #453230);
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

.g0laajs1z {
  fill: var(--svg-color--323232, #323232);
  fill-rule: evenodd;
  d: path("M17.866 6.973a.72.72 0 0 0-.488-.028a.1.1 0 0 1-.066-.189a.92.92 0 0 1 .637.035a.1.1 0 1 1-.083.182");
}

.gezrebbgs {
  stop-color: var(--svg-color--e03932, #E03932);
  stop-opacity: 0;
}

.h846rykft {
  stop-color: var(--svg-color--48403e, #48403E);
  stop-opacity: 0;
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.i176-27ra {
  stop-color: var(--svg-color--5d4947, #5D4947);
  stop-opacity: 0;
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.it71nu7tw {
  d: path("m5.232 17.009l21.725-.022v6.25L8.949 23.12z");
}

.j9b-420yy {
  stop-color: var(--svg-color--2f2529, #2F2529);
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.jaxrm4b9t {
  stop-color: var(--svg-color--665453, #665453);
  stop-opacity: 0;
}

.jqmxz7bhg {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.806c.048.013.099-.026.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.05-.434.031-.5.277l-.003.01c-.015.06.01.119.066.134z");
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k_odxeboz {
  d: path("M14.713 7.729h1.744v2h-1.744z");
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k5y4d_b1p {
  stop-color: var(--svg-color--211b1e, #211B1E);
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.k7xyk1boq {
  stop-color: var(--svg-color--594947, #594947);
}

.k8-07jblo {
  d: path("M11.366 20.35a1.917 1.917 0 1 1 2.712 2.711l-2.468 2.47a1.917 1.917 0 1 1-2.712-2.711z");
}

.ka9zhabzx {
  d: path("M16.504 13.808c-.713-.332-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.278 2.684 1.352c.395.093 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.399a10 10 0 0 1-2.246-.718");
}

.kgie-nbve {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.434c.016-.037.07-.048.119-.026s.075.07.059.106c-.017.036-.07.048-.119.026s-.075-.07-.059-.106");
}

.lon_-ybsm {
  stop-color: var(--svg-color--5d4947, #5D4947);
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m65xr0s5g {
  d: path("M13.872 7.59c.085-.193.296-.226.39-.218c-.39-.766-.085-2.687.65-3.047a1.77 1.77 0 0 1 1.577.023c.243.133.567.446 1.27.41c.645-.032 1 .332 1.004.692s-.117.844-.637.96c-.52.118-.758-.07-1.394-.148c-.492-.06-.866.278-.989.47c-.183.29-.615.914-.75 1.136c-.168.277-.406.402-.73.34c-.324-.063-.496-.375-.39-.618");
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.n3cyb-3sq {
  stop-color: var(--svg-color--493534, #493534);
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.nvujmsdui {
  stop-color: var(--svg-color--503634, #503634);
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.pumz-pbhp {
  d: path("M9.598 13.753c-.243.895-.203 1.762-.11 2.024l6.309-.063z");
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.qkwj62byu {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 13.087px;
  rx: 0.318px;
}

.qs52py0bf {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.551px;
  rx: 1.095px;
}

.qxt6awing {
  stop-color: var(--svg-color--665453, #665453);
}

.r_erdlb4g {
  stop-color: var(--svg-color--ff9954, #FF9954);
}

.rj26_kbww {
  stop-color: var(--svg-color--594646, #594646);
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.s08zmubju {
  d: path("M3.504 24.472c-.775-.425-1.254-.422-1.445-.422v5.937H29.94V24.05c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.s13t8gbqa {
  stop-color: var(--svg-color--665351, #665351);
  stop-opacity: 0;
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.seb5mcv_j {
  d: path("M18.232 8.085c-.081-.147-.066-.411-.047-.504l-.445 1.02c.14.074.378.139.515-.032c.098-.12.079-.3-.023-.484");
}

.sseixlt9y {
  fill: var(--svg-color--4d4749, #4D4749);
  d: path("M17.068 6.06c-.675-.137-1.198.188-1.375.368c.632-1 1.43-.656 2.054-.68c.5-.018.709-.346.75-.507c.006.171.064.53-.144.714c-.256.228-.442.278-1.285.106");
}

.sydryhb-w {
  stop-color: var(--svg-color--3e2227, #3E2227);
}

.t8zorw1yi {
  d: path("M17.641 7.805q.045-.05.061-.11c.027-.099-.019-.206-.097-.227c-.08-.021-.17.04-.198.148a.3.3 0 0 0-.002.126z");
}

.tc1_y3b9f {
  d: path("M15.931 9.69c-.914-.453-1.535-1.234-1.71-1.617l.662-1.593a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.002.372.067c.288.182.576.644.369 1.475c-.229 1.081-.501 1.744-.749 2.227c-.177.344-.533.572-.916.506a3.2 3.2 0 0 1-.718-.217");
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.w_eq7titt {
  stop-color: var(--svg-color--665351, #665351);
}

.w1kjbmbah {
  stop-color: var(--svg-color--f9663c, #F9663C);
}

.weit5gbyi {
  fill: var(--svg-color--fa623e, #FA623E);
  d: path("M11.168 10.597c-1.006 1.231-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.wj4eoubdt {
  d: path("M17.72 7.827c.02-.037.038-.064.051-.113c.048-.178-.02-.355-.169-.394c-.138-.037-.296.079-.343.256a.5.5 0 0 0-.012.124z");
}

.wj7cv1bow {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M16.98 8.494a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.184a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.133");
}

.wqxg4jbgc {
  stop-color: var(--svg-color--286ec5, #286EC5);
  stop-opacity: 0;
}

.wvez-gyvu {
  stop-color: var(--svg-color--86bf45, #86BF45);
}

.wwotuurhh {
  stop-color: var(--svg-color--528c3f, #528C3F);
  stop-opacity: 0;
}

.x8rdo-2id {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.403 11.748c.292.35.89.871 1.805 1.165c1.438.46 1.734.515 2.36.726");
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.y6c_odbaq {
  stop-color: var(--svg-color--594646, #594646);
  stop-opacity: 0;
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.yte4k7nua {
  stop-color: var(--svg-color--48403e, #48403E);
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

</style>
