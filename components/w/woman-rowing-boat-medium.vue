<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivJdURc)" transform="rotate(39.16 14.713 7.741)" class="eo57x_bag"/><path fill="url(#iT1c5Ae)" class="emoh--4km"/><g filter="url(#iNO8Hsd)"><path fill="url(#iBE4zlc)" class="qf_4t_b1g"/><path fill="url(#illjpwe)" class="qf_4t_b1g"/><path fill="url(#ia8qzab)" class="qf_4t_b1g"/></g><path clip-rule="evenodd" class="jebfk-b2o"/><g filter="url(#iRImLcb)"><path clip-rule="evenodd" class="lw-gqrb6o"/></g><g filter="url(#ijlJyJc)"><path class="bwrz-lbdz"/><path fill="url(#iu1fO8M)" class="s8s51hbxy"/></g><path fill="url(#igrtKxb)" class="qpyd96d_v"/><path fill="url(#iVJ5Cab)" class="rwne-c96c"/><path fill="url(#iDYhfxd)" class="rwne-c96c"/><path fill="url(#iLUMnre)" class="rwne-c96c"/><path fill="url(#iHSuMTc)" class="rwne-c96c"/><g filter="url(#ix0Opid)"><path fill="url(#iz2H0xc)" class="mzxdm4s4q"/><path fill="url(#irMLp7b)" class="mzxdm4s4q"/><path fill="url(#iA0G8Tc)" class="mzxdm4s4q"/></g><g filter="url(#ighNard)"><rect fill="url(#iusKrSq)" class="y3gtdubfa"/><rect fill="url(#irUgGln)" class="y3gtdubfa"/><rect fill="url(#iOO07ye)" class="y3gtdubfa"/><rect fill="url(#ipuPHYb)" class="y3gtdubfa"/></g><rect fill="url(#ikkw5Nb)" transform="rotate(-21.787 19.523 13.1)" class="ss1dyccvx"/><path fill="url(#ibrUCBd)" class="bw_inn-iq"/><path fill="url(#iT4Y9Wc)" class="bw_inn-iq"/><path fill="url(#iqSoqsd)" class="bw_inn-iq"/><g filter="url(#iCvfArd)"><path fill="url(#iDleAud)" class="mvs0lobdr"/></g><g filter="url(#iV29lcc)"><path fill="url(#i97bB0b)" class="y11okfqst"/><path fill="url(#is1T8pe)" class="y11okfqst"/><path fill="url(#irTKOuc)" class="y11okfqst"/></g><g filter="url(#isy63Ca)"><path class="rdn825_3n"/><path fill="url(#iSYHzsb)" class="tijzvkb_f"/></g><g filter="url(#iXG3mAe)"><path stroke="url(#iatPLpb)" class="u6vhnhjvj"/></g><g filter="url(#iJaw5Ob)"><path fill="url(#iCl0RAe)" class="dfnag2b3r"/></g><path fill="url(#igQbcjd)" class="ww-_e-flk"/><path class="cdiws7bbk"/><path fill="url(#iNqoPPb)" class="wbxoep2og"/><path fill="url(#ioeTv6c)" class="mclljmbve"/><path class="r8bvbnbmq"/><g filter="url(#iz53glr)"><path fill="url(#iZYA6Sc)" class="l3p_vvbjf"/><path fill="url(#iUTiode)" class="l3p_vvbjf"/></g><defs><radialGradient id="ivJdURc" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.304 9.674)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="bbppnek8h"/><stop offset="1" class="wj36x1bhr"/></radialGradient><radialGradient id="iT1c5Ae" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.25 10.54)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="i531rrbeb"/><stop offset="1" class="zto3p_lef"/></radialGradient><radialGradient id="iBE4zlc" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.166 5.316)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="gyymo5b9p"/><stop offset="1" class="ikvhpob1k"/></radialGradient><radialGradient id="illjpwe" cx="0" cy="0" r="1" gradientTransform="rotate(107.289 5.843 10.223)scale(.61776 .64399)" gradientUnits="userSpaceOnUse"><stop class="v5j-79bqk"/><stop offset="1" class="r5lh8e62q"/></radialGradient><radialGradient id="ia8qzab" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.175)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="uee_89odc"/><stop offset="1" class="g491cdewz"/></radialGradient><radialGradient id="iu1fO8M" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.073 15.259)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ik1b347lr"/><stop offset="1" class="fyswmcz3l"/></radialGradient><radialGradient id="igrtKxb" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.262 48.672)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="iLUMnre" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 22.062)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="iHSuMTc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 21.968)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iz2H0xc" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.212 15.109)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="irMLp7b" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.9 10.425)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="iA0G8Tc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.156)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="irUgGln" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.187)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="iOO07ye" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.658)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="ipuPHYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.957 16.437)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="ikkw5Nb" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 20.018 13.36)" gradientUnits="userSpaceOnUse"><stop class="yj2immbwm"/><stop offset="1" class="g-0n7qbjd"/></radialGradient><radialGradient id="ibrUCBd" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.306 10.788)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="iDleAud" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 21)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="is1T8pe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 28.968)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iSYHzsb" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29687 .16254 .33364 20.747 13.948)" gradientUnits="userSpaceOnUse"><stop class="roxpyebqa"/><stop offset="1" class="xi66vkmon"/></radialGradient><radialGradient id="iCl0RAe" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.187)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="d8l2uy9_q"/><stop offset="1" class="ml-wi-9ur"/></radialGradient><radialGradient id="igQbcjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.36061 .26664 -.28066 -.37957 17.457 7.308)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><radialGradient id="iNqoPPb" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 17.543 7.796)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="ioeTv6c" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.531)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><radialGradient id="iZYA6Sc" cx="0" cy="0" r="1" gradientTransform="rotate(163.724 8.88 4.332)scale(5.51064 6.88411)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="d91_czbbg"/><stop offset="1" class="j6q8gsuid"/></radialGradient><radialGradient id="iUTiode" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35938 .17969 -.15962 -1.20756 18.854 5.354)" gradientUnits="userSpaceOnUse"><stop class="qmznax6be"/><stop offset="1" class="n6bvr1bxo"/></radialGradient><filter id="iNO8Hsd" width="4.364" height="4.439" x="14.22" y="5.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.294118 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23071"/></filter><filter id="iRImLcb" width=".763" height=".367" x="17.245" y="6.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23071"/></filter><filter id="ijlJyJc" width="6.377" height="6.141" x="9.574" y="8.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.321569 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23071"/></filter><filter id="ix0Opid" width="27.983" height="6.037" x="2.059" y="20.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23071"/></filter><filter id="ighNard" width="24.059" height="2.191" x="3.886" y="15.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23071"/></filter><filter id="iCvfArd" width="6.802" height="6.803" x="8.337" y="19.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23071"/></filter><filter id="iV29lcc" width="27.983" height="6.037" x="1.959" y="24.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23071"/></filter><filter id="isy63Ca" width="6.678" height="4.108" x="14.785" y="10.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.419608 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23071"/></filter><filter id="iXG3mAe" width="5.181" height="3.008" x="14.876" y="11.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23071" stdDeviation=".2"/></filter><filter id="iJaw5Ob" width="3.882" height="3.705" x="12.803" y="9.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.243137 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23071"/></filter><filter id="iz53glr" width="6.317" height="5.313" x="12.906" y="3.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0705882 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23071"/></filter><linearGradient id="iVJ5Cab" x1="25.051" x2="7.801" y1="18.906" y2="24.281" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="iDYhfxd" x1="27.145" x2="26.441" y1="20.468" y2="20.468" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="iusKrSq" x1="16.015" x2="16.395" y1="15.312" y2="18.843" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="iT4Y9Wc" x1="17.168" x2="17.582" y1="16.347" y2="16.742" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="iqSoqsd" x1="19.52" x2="19.184" y1="16.031" y2="15.679" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="i97bB0b" x1="18.457" x2="12.738" y1="23.437" y2="33.531" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="irTKOuc" x1="18.02" x2="18.02" y1="30" y2="29.718" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="iatPLpb" x1="15.804" x2="20.086" y1="12.292" y2="14.011" gradientUnits="userSpaceOnUse"><stop class="lhom_fbjg"/><stop offset="1" class="s09h4qbjb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-rowing-boat-medium" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
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

.bw_inn-iq {
  d: path("M21.334 12.315a.59.59 0 1 1 .829.839l-8.439 8.331a.59.59 0 0 1-.829-.839z");
}

.bwrz-lbdz {
  fill: var(--svg-color--7355bd, #7355BD);
  d: path("M11.168 10.61c-1.006 1.23-1.414 2.667-1.594 3.273l3.992 1.25c.125-1.024.75-2.72 1.172-3.375c.422-.657.489-.871.555-1.348s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.cdiws7bbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.819c.048.012.099-.027.124-.083l.003-.01c.066-.246-.096-.438-.295-.49c-.189-.051-.434.03-.5.277l-.003.01c-.015.059.01.118.066.133z");
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.d8l2uy9_q {
  stop-color: var(--svg-color--9178d3, #9178D3);
}

.d91_czbbg {
  stop-color: var(--svg-color--4f343a, #4F343A);
}

.dfnag2b3r {
  d: path("M13.004 11.11c.6.718 1.333 1.554 1.625 1.882l1.656-1.484c-.33-.396-1.117-1.303-1.617-1.766c-.625-.578-1.27-.191-1.469 0c-.172.166-.672.688-.195 1.367");
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

.emoh--4km {
  d: path("M18.232 8.097c-.081-.146-.066-.411-.047-.503l-.445 1.019c.14.074.378.14.515-.031c.098-.121.079-.301-.023-.485");
}

.eo57x_bag {
  d: path("M14.713 7.741h1.744v2h-1.744z");
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

.fyswmcz3l {
  stop-color: var(--svg-color--57399f, #57399F);
  stop-opacity: 0;
}

.g-0n7qbjd {
  stop-color: var(--svg-color--a28169, #A28169);
}

.g491cdewz {
  stop-color: var(--svg-color--b68e7e, #B68E7E);
  stop-opacity: 0;
}

.gyymo5b9p {
  stop-color: var(--svg-color--bc907a, #BC907A);
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

.ik1b347lr {
  stop-color: var(--svg-color--57399f, #57399F);
}

.ikvhpob1k {
  stop-color: var(--svg-color--ae7d72, #AE7D72);
}

.j6q8gsuid {
  stop-color: var(--svg-color--4a3237, #4A3237);
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.jebfk-b2o {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M16.98 8.506a.1.1 0 0 1 .132.05c.032.07.15.243.339.325a.1.1 0 0 1-.079.183a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.133");
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.l3p_vvbjf {
  d: path("M13.6 6.82c.332-.226.418-.44.515-1.093c.219-1.094.542-1.306.969-1.547c.449-.254 1.195-.187 1.703.195c.558.42.668.342 1.348.364c.722.023.972.496.988.91c.015.414-.207.98-.934 1.031c-.834.058-.875-.687-1.574-.531c-.596.133-.727 1.316-.976 1.797c-.159.305-.3 1.013-1.165 1.21c-.921.212-1.68-.562-1.554-1.327c.1-.613.382-.805.68-1.008");
}

.lhom_fbjg {
  stop-color: var(--svg-color--ba9080, #BA9080);
}

.lw-gqrb6o {
  fill: var(--svg-color--594343, #594343);
  fill-rule: evenodd;
  d: path("M17.866 6.985a.72.72 0 0 0-.488-.027a.1.1 0 0 1-.066-.19a.92.92 0 0 1 .637.035a.1.1 0 1 1-.083.182");
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.mclljmbve {
  d: path("M17.641 7.817q.045-.05.061-.11c.027-.098-.019-.205-.097-.227c-.08-.02-.17.04-.198.148a.3.3 0 0 0-.002.126z");
}

.ml-wi-9ur {
  stop-color: var(--svg-color--7151be, #7151BE);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.mvs0lobdr {
  d: path("M11.366 20.363a1.917 1.917 0 1 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 0 1-2.712-2.711z");
}

.mzxdm4s4q {
  d: path("M3.504 20.984c-.775-.425-1.254-.422-1.445-.422V26.5H29.94v-5.938c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.n6bvr1bxo {
  stop-color: var(--svg-color--5f4746, #5F4746);
  stop-opacity: 0;
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.qf_4t_b1g {
  d: path("M15.931 9.742c-.914-.453-1.535-1.235-1.71-1.618l.662-1.592a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.003.372.066c.288.183.576.645.369 1.476c-.229 1.08-.501 1.744-.749 2.226c-.177.345-.533.572-.916.506a3.2 3.2 0 0 1-.718-.216");
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.qmznax6be {
  stop-color: var(--svg-color--5f4746, #5F4746);
}

.qpyd96d_v {
  d: path("M9.598 13.765c-.243.895-.203 1.762-.11 2.024l6.309-.063z");
}

.r5lh8e62q {
  stop-color: var(--svg-color--c9a289, #C9A289);
  stop-opacity: 0;
}

.r8bvbnbmq {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.446c.016-.036.07-.048.119-.026s.075.07.059.106c-.017.037-.07.049-.119.027s-.075-.07-.059-.107");
}

.rdn825_3n {
  fill: var(--svg-color--b59073, #B59073);
  d: path("M16.504 13.82c-.713-.331-1.443-.966-1.719-1.242l1.281-1.191c1.157 1.109 2.375 1.278 2.684 1.351c.395.094 1.538.3 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.roxpyebqa {
  stop-color: var(--svg-color--c59e89, #C59E89);
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.rwne-c96c {
  d: path("M5.232 17.021L26.957 17v6.25l-18.008-.117z");
}

.s09h4qbjb {
  stop-color: var(--svg-color--ba9080, #BA9080);
  stop-opacity: 0;
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.s8s51hbxy {
  d: path("M11.168 10.61c-1.006 1.23-1.414 2.667-1.594 3.273l3.992 1.25c.125-1.024.75-2.72 1.172-3.375c.422-.657.489-.871.555-1.348s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.ss1dyccvx {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 13.099px;
  rx: 0.318px;
}

.tijzvkb_f {
  d: path("M16.504 13.82c-.713-.331-1.443-.966-1.719-1.242l1.281-1.191c1.157 1.109 2.375 1.278 2.684 1.351c.395.094 1.538.3 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
}

.u6vhnhjvj {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.43 11.76c.291.35.889.871 1.804 1.165c1.438.46 1.734.515 2.36.726");
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

.wbxoep2og {
  d: path("M17.72 7.84c.02-.038.038-.065.051-.114c.048-.177-.02-.354-.169-.394c-.138-.037-.296.08-.343.257a.5.5 0 0 0-.012.123z");
}

.wj36x1bhr {
  stop-color: var(--svg-color--9c7060, #9C7060);
}

.wqxg4jbgc {
  stop-color: var(--svg-color--286ec5, #286EC5);
  stop-opacity: 0;
}

.wvez-gyvu {
  stop-color: var(--svg-color--86bf45, #86BF45);
}

.ww-_e-flk {
  d: path("m16.914 7.516l.116.063l.57-.29c-.28-.16-.543-.126-.722.026c-.068.057-.042.16.036.201");
}

.wwotuurhh {
  stop-color: var(--svg-color--528c3f, #528C3F);
  stop-opacity: 0;
}

.xi66vkmon {
  stop-color: var(--svg-color--c59e89, #C59E89);
  stop-opacity: 0;
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.y11okfqst {
  d: path("M3.504 24.484c-.775-.425-1.254-.422-1.445-.422V30H29.94v-5.938c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.y3gtdubfa {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.563px;
  rx: 1.095px;
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

.zto3p_lef {
  stop-color: var(--svg-color--b68375, #B68375);
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

</style>
