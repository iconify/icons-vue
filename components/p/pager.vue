<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFIBuPb)"><path fill="url(#ijgguqH)" class="um8n_v4ir"/><path fill="url(#ik56B9c)" class="um8n_v4ir"/></g><g filter="url(#ipkfL7c)" class="o51_cfbva"><path stroke="url(#itWTR7c)" class="qfq01xbaa"/><path stroke="url(#iIwgTNe)" class="qfq01xbaa"/><path stroke="url(#iXApqKd)" class="qfq01xbaa"/></g><g filter="url(#iwhGv1b)"><path class="vmss3ibox"/></g><g filter="url(#igXRFod)"><path fill="url(#iZq1Lqe)" class="qfq01xbaa"/><path fill="url(#iRxjexe)" class="qfq01xbaa"/></g><path class="x8p9ivbar"/><path class="e401xi9tt"/><path class="u1qx16bhn"/><path class="zshy_oi1x"/><path class="cj4f7qbaa"/><path class="fb6reybxa"/><path class="ccr487bip"/><path class="miviz4bvw"/><g filter="url(#iX8i7Gb)"><path class="o34tdhb5r"/></g><g filter="url(#iJMagte)"><path class="ciwx2dbdd"/></g><g filter="url(#iKzP8Tc)"><path class="qppksfb3j"/><path fill="url(#imKGssc)" class="p85ic3b5n"/></g><g filter="url(#ieG1GZb)"><path stroke="url(#i28sVdc)" class="rnm0h51vk"/></g><defs><filter id="iFIBuPb" width="28.953" height="22.422" x="2.023" y="8.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.27451 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19194"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.192157 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19194" result="effect2_innerShadow_18_19194"/></filter><filter id="ipkfL7c" width="24.994" height="13.088" x="3.573" y="10.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19194" stdDeviation=".15"/></filter><filter id="iwhGv1b" width="24.194" height="12.287" x="3.973" y="10.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19194" stdDeviation=".1"/></filter><filter id="igXRFod" width="24.094" height="12.188" x="3.773" y="11.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.764706 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19194"/></filter><filter id="iX8i7Gb" width="8.698" height="4.037" x="3.531" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.156863 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19194"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19194" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.929412 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19194"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.670588 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19194" result="effect3_innerShadow_18_19194"/></filter><filter id="iJMagte" width="8.698" height="4.037" x="13.031" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.156863 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19194"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19194" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.929412 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19194"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.670588 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19194" result="effect3_innerShadow_18_19194"/></filter><filter id="iKzP8Tc" width="5.714" height="4.037" x="22.531" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.156863 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_19194"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_19194" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.192157 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_19194"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.101961 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19194" result="effect3_innerShadow_18_19194"/></filter><filter id="ieG1GZb" width="26.93" height="20.5" x="3.281" y="9.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19194" stdDeviation=".375"/></filter><linearGradient id="ijgguqH" x1="16" x2="16" y1="9.031" y2="29.953" gradientUnits="userSpaceOnUse"><stop class="byvqk_rjm"/><stop offset="1" class="tc4ti_bxn"/></linearGradient><linearGradient id="itWTR7c" x1="16.07" x2="16.07" y1="11.156" y2="22.844" gradientUnits="userSpaceOnUse"><stop class="gvne-cb9p"/><stop offset="1" class="qg9vokh3i"/></linearGradient><linearGradient id="iIwgTNe" x1="3.93" x2="18.398" y1="19.313" y2="15.969" gradientUnits="userSpaceOnUse"><stop offset=".065" class="jcq8fk33g"/><stop offset=".342" class="dao__8bjx"/></linearGradient><linearGradient id="iXApqKd" x1="14.961" x2="14.961" y1="23.406" y2="22.953" gradientUnits="userSpaceOnUse"><stop offset=".194" class="jcq8fk33g"/><stop offset="1" class="dao__8bjx"/></linearGradient><linearGradient id="iZq1Lqe" x1="12.242" x2="25.497" y1="22.188" y2="7.901" gradientUnits="userSpaceOnUse"><stop class="aitqtr43m"/><stop offset="1" class="ehb850buh"/></linearGradient><linearGradient id="iRxjexe" x1="18.242" x2="18.242" y1="24.031" y2="20.688" gradientUnits="userSpaceOnUse"><stop class="y-i-nub_h"/><stop offset="1" class="sui_r094h"/></linearGradient><linearGradient id="i28sVdc" x1="29.086" x2="16.652" y1="9.597" y2="28.711" gradientUnits="userSpaceOnUse"><stop class="obyxzabby"/><stop offset=".873" class="nreu55bjg"/></linearGradient><radialGradient id="ik56B9c" cx="0" cy="0" r="1" gradientTransform="rotate(138.468 12.938 10.526)scale(1.69894 2.96575)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="qcmt5-bpt"/><stop offset="1" class="etvq2l69v"/></radialGradient><radialGradient id="imKGssc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .75 -1.32247 -1.87348 27.648 25.719)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="at79kiw9q"/><stop offset="1" class="tp01uccpe"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pager" /></template>
<style>
.aitqtr43m {
  stop-color: var(--svg-color--4de399, #4DE399);
}

.at79kiw9q {
  stop-color: var(--svg-color--ff6588, #FF6588);
}

.byvqk_rjm {
  stop-color: var(--svg-color--5f4675, #5F4675);
}

.ccr487bip {
  fill: var(--svg-color--3b897b, #3B897B);
  d: path("M21.598 14.484a.984.984 0 1 1 1.968 0V15.5a.984.984 0 1 1-1.968 0z");
}

.ciwx2dbdd {
  fill: var(--svg-color--e1d9ea, #E1D9EA);
  d: path("M13.531 26.469A1.47 1.47 0 0 1 15 25h4.96a1.469 1.469 0 1 1 0 2.938H15a1.47 1.47 0 0 1-1.469-1.47");
}

.cj4f7qbaa {
  fill: var(--svg-color--3b897b, #3B897B);
  d: path("M17.566 14.484a.984.984 0 1 1 1.97 0V15.5a.984.984 0 0 1-1.97 0z");
}

.dao__8bjx {
  stop-color: var(--svg-color--6e6479, #6E6479);
  stop-opacity: 0;
}

.e401xi9tt {
  fill: var(--svg-color--3b897c, #3B897C);
  d: path("M8.586 18.5a.984.984 0 1 1 1.969 0v1.016a.984.984 0 1 1-1.97 0z");
}

.ehb850buh {
  stop-color: var(--svg-color--47c282, #47C282);
}

.etvq2l69v {
  stop-color: var(--svg-color--847297, #847297);
  stop-opacity: 0;
}

.fb6reybxa {
  fill: var(--svg-color--3b897c, #3B897C);
  d: path("M17.566 18.5a.984.984 0 1 1 1.97 0v1.016a.984.984 0 0 1-1.97 0z");
}

.ft5dv1b6b {
  fill: none;
}

.gvne-cb9p {
  stop-color: var(--svg-color--543576, #543576);
}

.jcq8fk33g {
  stop-color: var(--svg-color--6e6479, #6E6479);
}

.miviz4bvw {
  fill: var(--svg-color--3c897c, #3C897C);
  d: path("M21.598 18.5a.984.984 0 1 1 1.968 0v1.016a.984.984 0 1 1-1.968 0z");
}

.nreu55bjg {
  stop-color: var(--svg-color--837196, #837196);
  stop-opacity: 0;
}

.o34tdhb5r {
  fill: var(--svg-color--e1d9ea, #E1D9EA);
  d: path("M4.031 26.469A1.47 1.47 0 0 1 5.5 25h4.96a1.469 1.469 0 1 1 0 2.938H5.5a1.47 1.47 0 0 1-1.469-1.47");
}

.o51_cfbva {
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
}

.obyxzabby {
  stop-color: var(--svg-color--837196, #837196);
}

.p85ic3b5n {
  d: path("M23.031 26.469A1.47 1.47 0 0 1 24.5 25h1.977a1.469 1.469 0 0 1 0 2.938H24.5a1.47 1.47 0 0 1-1.469-1.47");
}

.qcmt5-bpt {
  stop-color: var(--svg-color--847297, #847297);
}

.qfq01xbaa {
  d: path("M4.273 12.056a.9.9 0 0 1 .9-.9h21.794a.9.9 0 0 1 .9.9v9.888a.9.9 0 0 1-.9.9H5.173a.9.9 0 0 1-.9-.9z");
}

.qg9vokh3i {
  stop-color: var(--svg-color--42384f, #42384F);
}

.qppksfb3j {
  fill: var(--svg-color--f53d67, #F53D67);
  d: path("M23.031 26.469A1.47 1.47 0 0 1 24.5 25h1.977a1.469 1.469 0 0 1 0 2.938H24.5a1.47 1.47 0 0 1-1.469-1.47");
}

.rnm0h51vk {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M4.031 10.188h23.555a1.5 1.5 0 0 1 1.5 1.5v15.804c.008.315-.16.945-.895.945");
}

.sui_r094h {
  stop-color: var(--svg-color--4de299, #4DE299);
  stop-opacity: 0;
}

.tc4ti_bxn {
  stop-color: var(--svg-color--50425d, #50425D);
}

.tp01uccpe {
  stop-color: var(--svg-color--ff6588, #FF6588);
  stop-opacity: 0;
}

.u1qx16bhn {
  fill: var(--svg-color--3b897b, #3B897B);
  d: path("M12.617 14.484a.984.984 0 1 1 1.969 0V15.5a.984.984 0 1 1-1.969 0z");
}

.um8n_v4ir {
  d: path("M2.023 11.531a2.5 2.5 0 0 1 2.5-2.5h22.954a2.5 2.5 0 0 1 2.5 2.5v15.922a2.5 2.5 0 0 1-2.5 2.5H4.523a2.5 2.5 0 0 1-2.5-2.5z");
}

.vmss3ibox {
  stroke: var(--svg-color--2e5d4b, #2E5D4B);
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M4.273 12.056a.9.9 0 0 1 .9-.9h21.794a.9.9 0 0 1 .9.9v9.888a.9.9 0 0 1-.9.9H5.173a.9.9 0 0 1-.9-.9z");
}

.x8p9ivbar {
  fill: var(--svg-color--3a887a, #3A887A);
  d: path("M8.586 14.484a.984.984 0 1 1 1.969 0V15.5a.984.984 0 1 1-1.97 0z");
}

.y-i-nub_h {
  stop-color: var(--svg-color--4be18c, #4BE18C);
}

.zshy_oi1x {
  fill: var(--svg-color--3c897c, #3C897C);
  d: path("M12.617 18.5a.984.984 0 1 1 1.969 0v1.016a.984.984 0 1 1-1.969 0z");
}

</style>
