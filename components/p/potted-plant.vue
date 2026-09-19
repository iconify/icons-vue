<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="zeu4vxbye"/><path class="c9r1s3y9h"/><path fill="url(#iCRGWsb)" class="s89j5j_wp"/><path class="p22rg8y4u"/><path stroke="url(#iOdCgWb)" class="k4q9a6g8v"/><path class="n96md_8zt"/><path stroke="url(#ibuhrrd)" class="qncde3bmb"/><path class="kbgil-b7k"/><path stroke="url(#izFYSID)" class="dgih7eteo"/><path stroke="url(#i0fjYCe)" class="dgih7eteo"/><path class="j4rt0fbtz"/><path stroke="url(#i6UyRpd)" class="ob8crreel"/><path stroke="url(#i0Dx0Rc)" class="ob8crreel"/><g filter="url(#ib0BZCe)"><path stroke="url(#iH7YOWb)" class="vzps08f7s"/></g><g filter="url(#i5W1qfc)"><path stroke="url(#iAs2jud)" class="zah-i5k1k"/></g><g filter="url(#izZKVja)"><path stroke="url(#ikXFRKb)" class="etshtp3ry"/></g><g filter="url(#iORKVTb)"><path stroke="url(#iE562Yd)" class="dttq1_8vm"/></g><g filter="url(#ikKp0Yb)"><path stroke="url(#ix7mhfe)" class="fvui35bbq"/></g><path fill="url(#i3mpDke)" class="dvmdc1g4e"/><path fill="url(#iM8EiPe)" class="jpi7n7b8v"/><g filter="url(#i3Ko5Fd)"><path fill="url(#igo1ICb)" class="zcx_5m55z"/></g><g filter="url(#ifwcwRc)"><path class="qgpv-veie"/><path fill="url(#iLQTKge)" class="rf50sx_la"/></g><g filter="url(#i0uTeBd)"><path class="xpwuc_uvl"/><path fill="url(#itEP3um)" class="rx2joyb8z"/></g><g filter="url(#isYg6Xd)"><path class="vps17tbgl"/><path fill="url(#i98WkIc)" class="y7t_4cb0s"/><path fill="url(#iCwwOcd)" class="y7t_4cb0s"/></g><g filter="url(#i9FpDpe)"><path class="y6aspqxqz"/><path fill="url(#iiNRh1c)" class="dimvvtd3s"/><path fill="url(#i0gAuXd)" class="dimvvtd3s"/></g><path fill="url(#iG0lzuw)" class="dnllgcbhm"/><path fill="url(#ijJWAPb)" class="dnllgcbhm"/><path fill="url(#iGW5qhd)" class="dnllgcbhm"/><path fill="url(#iB4ybBb)" class="dnllgcbhm"/><path fill="url(#ieNgDCo)" class="y03eh8btp"/><path fill="url(#iIeWDgb)" class="y03eh8btp"/><path fill="url(#if6nF8d)" class="y03eh8btp"/><path fill="url(#ipxaLEo)" class="y03eh8btp"/><g filter="url(#i4Cuvxe)"><path stroke="url(#iQnED9b)" class="x51ej5a2k"/></g><g filter="url(#ikdVGpb)"><path stroke="url(#iszVxre)" class="cffqmhpww"/></g><g filter="url(#iad420M)"><path stroke="url(#ii2cQjb)" class="p72c7dbjj"/></g><g filter="url(#iCDYoHd)"><path stroke="url(#ioqR2Ne)" class="s9kv0ab0u"/></g><defs><linearGradient id="iCRGWsb" x1="17.134" x2="17.134" y1="8.946" y2="9.703" gradientUnits="userSpaceOnUse"><stop class="ib7xqgkhp"/><stop offset="1" class="u4osclbtg"/></linearGradient><linearGradient id="iOdCgWb" x1="12.969" x2="13.198" y1="16.309" y2="15.721" gradientUnits="userSpaceOnUse"><stop class="kge4rwboy"/><stop offset="1" class="b_j_tge9g"/></linearGradient><linearGradient id="ibuhrrd" x1="13.826" x2="14.104" y1="11.457" y2="10.69" gradientUnits="userSpaceOnUse"><stop class="kge4rwboy"/><stop offset="1" class="b_j_tge9g"/></linearGradient><linearGradient id="i0fjYCe" x1="17.393" x2="17.273" y1="17.445" y2="17.076" gradientUnits="userSpaceOnUse"><stop class="kge4rwboy"/><stop offset="1" class="b_j_tge9g"/></linearGradient><linearGradient id="i6UyRpd" x1="18.807" x2="18.628" y1="11.636" y2="11.271" gradientUnits="userSpaceOnUse"><stop class="kge4rwboy"/><stop offset="1" class="b_j_tge9g"/></linearGradient><linearGradient id="i0Dx0Rc" x1="19.076" x2="18.349" y1="11.148" y2="11.346" gradientUnits="userSpaceOnUse"><stop class="kge4rwboy"/><stop offset="1" class="b_j_tge9g"/></linearGradient><linearGradient id="iH7YOWb" x1="15.133" x2="17.836" y1="10.898" y2="11.828" gradientUnits="userSpaceOnUse"><stop class="l0f_j5bct"/><stop offset="1" class="m4flv29rr"/></linearGradient><linearGradient id="iAs2jud" x1="13.716" x2="18.05" y1="15.726" y2="16.907" gradientUnits="userSpaceOnUse"><stop class="ojwo--93a"/><stop offset="1" class="a0kcnaclq"/></linearGradient><linearGradient id="ikXFRKb" x1="17.982" x2="13.647" y1="16.616" y2="17.797" gradientUnits="userSpaceOnUse"><stop class="ojwo--93a"/><stop offset="1" class="a0kcnaclq"/></linearGradient><linearGradient id="iE562Yd" x1="19.337" x2="15.003" y1="10.757" y2="11.937" gradientUnits="userSpaceOnUse"><stop class="ojwo--93a"/><stop offset="1" class="a0kcnaclq"/></linearGradient><linearGradient id="ix7mhfe" x1="17.237" x2="17.237" y1="10.766" y2="19.236" gradientUnits="userSpaceOnUse"><stop class="l0f_j5bct"/><stop offset="1" class="ndrxg1rdh"/></linearGradient><linearGradient id="igo1ICb" x1="17.558" x2="17.558" y1="2.667" y2="8.692" gradientUnits="userSpaceOnUse"><stop class="nhmrt7bkg"/><stop offset="1" class="q0fv7fu-w"/></linearGradient><linearGradient id="ijJWAPb" x1="8.469" x2="13.031" y1="27.281" y2="26.996" gradientUnits="userSpaceOnUse"><stop class="lsqjcn62k"/><stop offset="1" class="jwjcv39gt"/></linearGradient><linearGradient id="iGW5qhd" x1="16.007" x2="16.007" y1="28.688" y2="30.313" gradientUnits="userSpaceOnUse"><stop offset=".011" class="l0hv0zbrz"/><stop offset="1" class="dcvagtbwk"/></linearGradient><linearGradient id="iB4ybBb" x1="16.007" x2="16.007" y1="23.924" y2="24.489" gradientUnits="userSpaceOnUse"><stop class="ki6b10w9w"/><stop offset="1" class="ud8ykhbsn"/></linearGradient><linearGradient id="iIeWDgb" x1="7.5" x2="17" y1="23.996" y2="23.996" gradientUnits="userSpaceOnUse"><stop class="ns_midbsq"/><stop offset="1" class="rnhwm4bxa"/></linearGradient><linearGradient id="if6nF8d" x1="16.007" x2="16.007" y1="23.547" y2="23.996" gradientUnits="userSpaceOnUse"><stop class="rvp85_ffc"/><stop offset="1" class="dcvagtbwk"/><stop offset="1" class="dmikjvkvf"/></linearGradient><linearGradient id="ipxaLEo" x1="16.007" x2="16.007" y1="19.675" y2="20.317" gradientUnits="userSpaceOnUse"><stop class="mxuteif2l"/><stop offset="1" class="lj6xi0btm"/></linearGradient><linearGradient id="iQnED9b" x1="24.132" x2="11.583" y1="20.39" y2="20.39" gradientUnits="userSpaceOnUse"><stop class="qxpy3pa0f"/><stop offset=".287" class="xpxlisbbn"/><stop offset=".795" class="qxpy3pa0f"/></linearGradient><linearGradient id="iszVxre" x1="18.325" x2="18.325" y1="2.533" y2="9.577" gradientUnits="userSpaceOnUse"><stop class="o00lmkb-k"/><stop offset="1" class="dktb3acec"/></linearGradient><filter id="ib0BZCe" width="3.461" height="1.563" x="14.226" y="10.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7581" stdDeviation=".125"/></filter><filter id="i5W1qfc" width="3.461" height="1.563" x="12.809" y="15.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7581" stdDeviation=".125"/></filter><filter id="izZKVja" width="3.461" height="1.563" x="15.427" y="16.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7581" stdDeviation=".125"/></filter><filter id="iORKVTb" width="3.461" height="1.563" x="16.782" y="10.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7581" stdDeviation=".125"/></filter><filter id="ikKp0Yb" width="2.287" height="10.156" x="15.645" y="8.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7581" stdDeviation=".125"/></filter><filter id="i3Ko5Fd" width="4.296" height="8.025" x="15.409" y="1.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7581" stdDeviation=".5"/></filter><filter id="ifwcwRc" width="6.309" height="5.568" x="7" y="10.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.784314 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7581"/></filter><filter id="i0uTeBd" width="6.311" height="5.567" x="8.474" y="5.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.784314 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7581"/></filter><filter id="isYg6Xd" width="6.309" height="5.568" x="17.886" y="11.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.784314 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7581"/></filter><filter id="i9FpDpe" width="6.309" height="5.568" x="18.706" y="5.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.784314 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7581"/></filter><filter id="i4Cuvxe" width="13.411" height="1" x="10.552" y="19.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7581" stdDeviation=".15"/></filter><filter id="ikdVGpb" width="2.512" height="6.759" x="16.832" y="1.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7581" stdDeviation=".3"/></filter><filter id="iad420M" width="4.263" height="4.075" x="10.556" y="6.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7581" stdDeviation=".2"/></filter><filter id="iCDYoHd" width="4.263" height="4.075" x="9.156" y="11.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7581" stdDeviation=".2"/></filter><radialGradient id="izFYSID" cx="0" cy="0" r="1" gradientTransform="rotate(163.277 7.903 9.818)scale(1.2153 1.86926)" gradientUnits="userSpaceOnUse"><stop class="kge4rwboy"/><stop offset="1" class="b_j_tge9g"/></radialGradient><radialGradient id="i3mpDke" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.3759 9.50361 0 14.6 20.22)" gradientUnits="userSpaceOnUse"><stop class="hxfylfiqx"/><stop offset="1" class="gr9tq2vve"/></radialGradient><radialGradient id="iM8EiPe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45976 0 0 -6.95372 18.654 5.68)" gradientUnits="userSpaceOnUse"><stop class="q27puqotp"/><stop offset="1" class="h114-wbki"/></radialGradient><radialGradient id="iLQTKge" cx="0" cy="0" r="1" gradientTransform="rotate(-150.851 8.79 5.076)scale(9.94444 3.64933)" gradientUnits="userSpaceOnUse"><stop class="sb-fllbbb"/><stop offset="1" class="xzjh9ubdx"/></radialGradient><radialGradient id="itEP3um" cx="0" cy="0" r="1" gradientTransform="matrix(-8.6875 -4.84375 1.77725 -3.1876 15.469 9)" gradientUnits="userSpaceOnUse"><stop class="sb-fllbbb"/><stop offset="1" class="xzjh9ubdx"/></radialGradient><radialGradient id="i98WkIc" cx="0" cy="0" r="1" gradientTransform="rotate(139.185 9.802 10.385)scale(8.09043 3.57458)" gradientUnits="userSpaceOnUse"><stop class="sb-fllbbb"/><stop offset="1" class="xzjh9ubdx"/></radialGradient><radialGradient id="iCwwOcd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24899 1.88738 -.4373 -.2894 24.195 11.251)" gradientUnits="userSpaceOnUse"><stop class="mwpl_zwir"/><stop offset="1" class="sqyxjvbye"/></radialGradient><radialGradient id="iiNRh1c" cx="0" cy="0" r="1" gradientTransform="rotate(139.185 11.261 7.718)scale(8.09043 3.57458)" gradientUnits="userSpaceOnUse"><stop class="sb-fllbbb"/><stop offset="1" class="xzjh9ubdx"/></radialGradient><radialGradient id="i0gAuXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24899 1.88738 -.4373 -.2894 25.015 5.612)" gradientUnits="userSpaceOnUse"><stop class="mwpl_zwir"/><stop offset="1" class="sqyxjvbye"/></radialGradient><radialGradient id="iG0lzuw" cx="0" cy="0" r="1" gradientTransform="rotate(-140.346 15.876 10.732)scale(8.03669 7.80374)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="vohh5_cuc"/><stop offset="1" class="p4jnobf6o"/></radialGradient><radialGradient id="ieNgDCo" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24257 -5.68749 4.40502 -4.06042 21.25 23.063)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wfahlun8y"/><stop offset="1" class="tb8xd3b0q"/></radialGradient><radialGradient id="ii2cQjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 .64062 -114.12824 -100.21118 13.36 8.016)" gradientUnits="userSpaceOnUse"><stop class="ougpbgb2l"/><stop offset="1" class="c49_mk4hp"/></radialGradient><radialGradient id="ioqR2Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 .64062 -114.12824 -100.21118 11.96 13.016)" gradientUnits="userSpaceOnUse"><stop class="ougpbgb2l"/><stop offset="1" class="c49_mk4hp"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:potted-plant" /></template>
<style>
.a0kcnaclq {
  stop-color: var(--svg-color--648746, #648746);
  stop-opacity: 0;
}

.b_j_tge9g {
  stop-color: var(--svg-color--4a5b3b, #4A5B3B);
  stop-opacity: 0;
}

.c49_mk4hp {
  stop-color: var(--svg-color--b3e468, #B3E468);
  stop-opacity: 0;
}

.c9r1s3y9h {
  fill: var(--svg-color--497426, #497426);
  d: path("M16.008 19.236c-.25 0-.45-.2-.45-.45v-3.13c0-1 .28-1.99.84-2.83c.47-.71.71-1.53.71-2.38v-2.1h.9v2.1c0 1.02-.29 2-.85 2.85c-.46.7-.7 1.52-.7 2.36v3.13c0 .25-.2.45-.45.45");
}

.cffqmhpww {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.682 2.799c.475.81 1.245 2.585.504 5.059");
}

.dcvagtbwk {
  stop-color: var(--svg-color--d37082, #D37082);
}

.dgih7eteo {
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-908px, 0.908px);
  d: path("m20.717 15.846l-4.84 1.45");
}

.dimvvtd3s {
  d: path("m21.358 6.846l3.26-.978a.24.24 0 0 1 .303.17a3.737 3.737 0 0 1-2.553 4.398l-3.262.979a.24.24 0 0 1-.303-.17a3.71 3.71 0 0 1 2.555-4.399");
}

.dktb3acec {
  stop-color: var(--svg-color--b9ee6e, #B9EE6E);
  stop-opacity: 0;
}

.dmikjvkvf {
  stop-color: var(--svg-color--d1556c, #D1556C);
}

.dnllgcbhm {
  d: path("m9.007 23.996l.78 4.69c.13.76.78 1.31 1.54 1.31h9.35c.76 0 1.42-.55 1.54-1.31l.79-4.69z");
}

.dttq1_8vm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.868 10.624l-2.71.812");
}

.dvmdc1g4e {
  d: path("M21.738 19.996a9.25 9.25 0 0 0-5.73-2c-2.15 0-4.14.75-5.73 2z");
}

.etshtp3ry {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m18.513 16.484l-2.711.812");
}

.ft5dv1b6b {
  fill: none;
}

.fvui35bbq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.558 8.986v1.662a4 4 0 0 1-.43 1.802l-.572 1.134a5 5 0 0 0-.536 2.252v2.556");
}

.gr9tq2vve {
  stop-color: var(--svg-color--714f4a, #714F4A);
}

.h114-wbki {
  stop-color: var(--svg-color--80b93f, #80B93F);
}

.hxfylfiqx {
  stop-color: var(--svg-color--774336, #774336);
}

.ib7xqgkhp {
  stop-color: var(--svg-color--3f6928, #3F6928);
}

.j4rt0fbtz {
  stroke: var(--svg-color--497426, #497426);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-908px, 0.908px);
  d: path("m22.007 10.066l-4.75 1.42");
}

.jpi7n7b8v {
  d: path("M17.458 2.066a5.104 5.104 0 0 0-.13 7.22c.09.09.24.1.33.01a5.104 5.104 0 0 0 .13-7.22c-.09-.1-.24-.1-.33-.01");
}

.jwjcv39gt {
  stop-color: var(--svg-color--b17a60, #B17A60);
  stop-opacity: 0;
}

.k4q9a6g8v {
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-908px, 0.908px);
  d: path("m11.288 15.126l4.84 1.45");
}

.kbgil-b7k {
  stroke: var(--svg-color--497426, #497426);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-908px, 0.908px);
  d: path("m20.717 15.846l-4.84 1.45");
}

.kge4rwboy {
  stop-color: var(--svg-color--4a5b3b, #4A5B3B);
}

.ki6b10w9w {
  stop-color: var(--svg-color--c87156, #C87156);
}

.l0f_j5bct {
  stop-color: var(--svg-color--608246, #608246);
}

.l0hv0zbrz {
  stop-color: var(--svg-color--d37082, #D37082);
  stop-opacity: 0;
}

.lj6xi0btm {
  stop-color: var(--svg-color--e6ab68, #E6AB68);
  stop-opacity: 0;
}

.lsqjcn62k {
  stop-color: var(--svg-color--b17a60, #B17A60);
}

.m4flv29rr {
  stop-color: var(--svg-color--608246, #608246);
  stop-opacity: 0;
}

.mwpl_zwir {
  stop-color: var(--svg-color--ace461, #ACE461);
}

.mxuteif2l {
  stop-color: var(--svg-color--e6ab68, #E6AB68);
}

.n96md_8zt {
  stroke: var(--svg-color--497426, #497426);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-908px, 0.908px);
  d: path("m11.888 10.076l5.27 1.58");
}

.ndrxg1rdh {
  stop-color: var(--svg-color--728c5b, #728C5B);
}

.nhmrt7bkg {
  stop-color: var(--svg-color--9cd740, #9CD740);
}

.ns_midbsq {
  stop-color: var(--svg-color--ae7f61, #AE7F61);
}

.o00lmkb-k {
  stop-color: var(--svg-color--b9ee6e, #B9EE6E);
}

.ob8crreel {
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-908px, 0.908px);
  d: path("m22.007 10.066l-4.75 1.42");
}

.ojwo--93a {
  stop-color: var(--svg-color--648746, #648746);
}

.ougpbgb2l {
  stop-color: var(--svg-color--b3e468, #B3E468);
}

.p22rg8y4u {
  stroke: var(--svg-color--497426, #497426);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-908px, 0.908px);
  d: path("m11.288 15.126l4.84 1.45");
}

.p4jnobf6o {
  stop-color: var(--svg-color--cf7d5b, #CF7D5B);
}

.p72c7dbjj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m11.156 6.953l1.106.376c.272.093.539.21.76.394c.492.411 1.118 1.156 1.197 2.105");
}

.q0fv7fu-w {
  stop-color: var(--svg-color--9cd740, #9CD740);
  stop-opacity: 0;
}

.q27puqotp {
  stop-color: var(--svg-color--a5d949, #A5D949);
}

.qgpv-veie {
  fill: var(--svg-color--7aad33, #7AAD33);
  d: path("m10.658 11.526l-3.261-.978a.24.24 0 0 0-.303.17a3.737 3.737 0 0 0 2.553 4.398l3.262.979a.24.24 0 0 0 .303-.17a3.716 3.716 0 0 0-2.554-4.399");
}

.qncde3bmb {
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-908px, 0.908px);
  d: path("m11.888 10.076l5.27 1.58");
}

.qxpy3pa0f {
  stop-color: var(--svg-color--fcd08f, #FCD08F);
  stop-opacity: 0;
}

.rf50sx_la {
  d: path("m10.658 11.526l-3.261-.978a.24.24 0 0 0-.303.17a3.737 3.737 0 0 0 2.553 4.398l3.262.979a.24.24 0 0 0 .303-.17a3.716 3.716 0 0 0-2.554-4.399");
}

.rnhwm4bxa {
  stop-color: var(--svg-color--ae7f61, #AE7F61);
  stop-opacity: 0;
}

.rvp85_ffc {
  stop-color: var(--svg-color--d1556c, #D1556C);
  stop-opacity: 0;
}

.rx2joyb8z {
  d: path("m12.128 6.736l-3.26-.978a.24.24 0 0 0-.304.172a3.74 3.74 0 0 0 2.563 4.396l3.26.978a.24.24 0 0 0 .304-.17a3.73 3.73 0 0 0-2.564-4.398");
}

.s89j5j_wp {
  d: path("M16.008 19.236c-.25 0-.45-.2-.45-.45v-3.13c0-1 .28-1.99.84-2.83c.47-.71.71-1.53.71-2.38v-2.1h.9v2.1c0 1.02-.29 2-.85 2.85c-.46.7-.7 1.52-.7 2.36v3.13c0 .25-.2.45-.45.45");
}

.s9kv0ab0u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.756 11.954l1.106.376c.272.093.539.209.76.393c.492.412 1.118 1.157 1.197 2.106");
}

.sb-fllbbb {
  stop-color: var(--svg-color--aae057, #AAE057);
}

.sqyxjvbye {
  stop-color: var(--svg-color--ace461, #ACE461);
  stop-opacity: 0;
}

.tb8xd3b0q {
  stop-color: var(--svg-color--e09369, #E09369);
}

.u4osclbtg {
  stop-color: var(--svg-color--3f6928, #3F6928);
  stop-opacity: 0;
}

.ud8ykhbsn {
  stop-color: var(--svg-color--c87156, #C87156);
  stop-opacity: 0;
}

.vohh5_cuc {
  stop-color: var(--svg-color--ffbb7a, #FFBB7A);
}

.vps17tbgl {
  fill: var(--svg-color--7aad33, #7AAD33);
  d: path("m20.538 12.486l3.26-.978a.24.24 0 0 1 .303.17a3.737 3.737 0 0 1-2.553 4.398l-3.262.979a.24.24 0 0 1-.303-.17a3.72 3.72 0 0 1 2.555-4.399");
}

.vzps08f7s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m14.602 10.766l2.71.812");
}

.wfahlun8y {
  stop-color: var(--svg-color--ffbd80, #FFBD80);
}

.x51ej5a2k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.052 20.472h12.41");
}

.xpwuc_uvl {
  fill: var(--svg-color--7aad33, #7AAD33);
  d: path("m12.128 6.736l-3.26-.978a.24.24 0 0 0-.304.172a3.74 3.74 0 0 0 2.563 4.396l3.26.978a.24.24 0 0 0 .304-.17a3.73 3.73 0 0 0-2.564-4.398");
}

.xpxlisbbn {
  stop-color: var(--svg-color--ffcd91, #FFCD91);
}

.xzjh9ubdx {
  stop-color: var(--svg-color--aae057, #AAE057);
  stop-opacity: 0;
}

.y03eh8btp {
  d: path("M23.507 23.996h-15c-.28 0-.5-.22-.5-.5v-3c0-.28.22-.5.5-.5h15c.28 0 .5.22.5.5v3c0 .28-.22.5-.5.5");
}

.y6aspqxqz {
  fill: var(--svg-color--7aad33, #7AAD33);
  d: path("m21.358 6.846l3.26-.978a.24.24 0 0 1 .303.17a3.737 3.737 0 0 1-2.553 4.398l-3.262.979a.24.24 0 0 1-.303-.17a3.71 3.71 0 0 1 2.555-4.399");
}

.y7t_4cb0s {
  d: path("m20.538 12.486l3.26-.978a.24.24 0 0 1 .303.17a3.737 3.737 0 0 1-2.553 4.398l-3.262.979a.24.24 0 0 1-.303-.17a3.72 3.72 0 0 1 2.555-4.399");
}

.zah-i5k1k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m13.184 15.594l2.711.812");
}

.zcx_5m55z {
  d: path("M17.488 2.721c-1.402 1.605-1.443 4.25-.09 5.911c.063.074.166.082.229.009c1.402-1.605 1.443-4.25.09-5.912c-.063-.081-.166-.081-.229-.008");
}

.zeu4vxbye {
  fill: var(--svg-color--497426, #497426);
  d: path("M16.008 19.236c-.25 0-.45-.2-.45-.45v-1.795a.15.15 0 0 0-.107-.144l-4.15-1.243a.15.15 0 0 1-.1-.187l.174-.582a.15.15 0 0 1 .186-.1l3.803 1.139a.15.15 0 0 0 .193-.144v-.074c0-1 .28-1.99.84-2.83q.207-.311.354-.649a.146.146 0 0 0-.094-.197L11.9 10.554a.15.15 0 0 1-.1-.187l.174-.582a.15.15 0 0 1 .187-.1l4.725 1.417a.146.146 0 0 0 .188-.12q.033-.266.033-.536v-1.95a.15.15 0 0 1 .15-.15h.6a.15.15 0 0 1 .15.15v1.95l-.002.13a.155.155 0 0 0 .197.154l3.53-1.056a.15.15 0 0 1 .187.101l.174.583a.15.15 0 0 1-.1.186l-4.08 1.22a.15.15 0 0 0-.102.105a5.1 5.1 0 0 1-.655 1.427c-.46.7-.7 1.52-.7 2.36v.791c0 .1.097.173.194.144l3.793-1.137a.15.15 0 0 1 .186.101l.175.582a.15.15 0 0 1-.101.187l-4.14 1.24a.15.15 0 0 0-.107.144v1.078c0 .25-.2.45-.45.45");
}

</style>
