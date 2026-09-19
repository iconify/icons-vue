<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipdzmzc)" class="zlcirlb_i"/><path fill="url(#inGiGye)" class="zlcirlb_i"/><path fill="url(#iWdj5sb)" class="zlcirlb_i"/><path fill="url(#iJ6EhLe)" class="zlcirlb_i"/><path fill="url(#id40bru)" class="w3ph53b_n"/><path fill="url(#iOStnje)" class="w3ph53b_n"/><path fill="url(#ie9nVLc)" class="w3ph53b_n"/><path fill="url(#iwlDRIc)" class="w3ph53b_n"/><path fill="url(#ibiTwNc)" class="trlacabza"/><path fill="url(#iqpQy1c)" class="trlacabza"/><g filter="url(#i2NaJ9d)"><path fill="url(#ikXuwIe)" class="m0xlkr4wf"/></g><path fill="url(#iHd7YEd)" class="m0xlkr4wf"/><g filter="url(#in86Zme)"><path class="ybn-7fb7j"/></g><defs><radialGradient id="ipdzmzc" cx="0" cy="0" r="1" gradientTransform="matrix(1.16102 -3.78737 2.95344 .90538 15.378 16.834)" gradientUnits="userSpaceOnUse"><stop class="uxkm7obed"/><stop offset="1" class="bi7un3blb"/></radialGradient><radialGradient id="iWdj5sb" cx="0" cy="0" r="1" gradientTransform="matrix(.75091 4.71875 -3.94577 .6279 15.213 13.613)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="f6s0yqbjc"/><stop offset=".909" class="jsjhui_2f"/></radialGradient><radialGradient id="id40bru" cx="0" cy="0" r="1" gradientTransform="rotate(-82.942 20.707 -.747)scale(8.25115 2.21235)" gradientUnits="userSpaceOnUse"><stop class="y2u37pdke"/><stop offset="1" class="q8ykaqean"/></radialGradient><radialGradient id="iOStnje" cx="0" cy="0" r="1" gradientTransform="matrix(-.81812 6.82953 -5.8375 -.69928 19.855 13.27)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="t92xnb1cp"/><stop offset=".965" class="z4oifbcew"/></radialGradient><radialGradient id="ie9nVLc" cx="0" cy="0" r="1" gradientTransform="matrix(4.02782 -5.99222 5.89113 3.95987 16.374 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".635" class="o5weycjxj"/><stop offset=".901" class="t56sokbfc"/></radialGradient><radialGradient id="ibiTwNc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.95584 -7.1769 1.55997 -.42512 24.31 20.633)" gradientUnits="userSpaceOnUse"><stop class="z309z-5wr"/><stop offset="1" class="ksw6i0btb"/></radialGradient><radialGradient id="iqpQy1c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11676 7.14566 -4.4133 -.68973 24.293 13.488)" gradientUnits="userSpaceOnUse"><stop offset=".872" class="sd4l66bbv"/><stop offset=".996" class="akuw0fa9u"/></radialGradient><radialGradient id="iHd7YEd" cx="0" cy="0" r="1" gradientTransform="rotate(24.814 -24.069 12.44)scale(6.40373 9.01085)" gradientUnits="userSpaceOnUse"><stop class="e-3i2yrdu"/><stop offset="1" class="c0c3k_b5h"/></radialGradient><linearGradient id="inGiGye" x1="17.255" x2="15.963" y1="17.532" y2="17.423" gradientUnits="userSpaceOnUse"><stop class="nv8g0j1ga"/><stop offset="1" class="tvg__8xpe"/></linearGradient><linearGradient id="iJ6EhLe" x1="13.24" x2="14.159" y1="15.306" y2="15.481" gradientUnits="userSpaceOnUse"><stop class="smfvy1b0j"/><stop offset="1" class="faw306w9s"/></linearGradient><linearGradient id="iwlDRIc" x1="21.554" x2="20.172" y1="17.183" y2="17.505" gradientUnits="userSpaceOnUse"><stop class="iapxnjmkg"/><stop offset="1" class="j2yizabta"/></linearGradient><linearGradient id="ikXuwIe" x1="9.586" x2="23.633" y1="22.503" y2="11.929" gradientUnits="userSpaceOnUse"><stop class="ly115miad"/><stop offset="1" class="j2u72qbdb"/></linearGradient><filter id="i2NaJ9d" width="29.13" height="19.251" x="2.215" y="5.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.639216 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6772"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.458824 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6772" result="effect2_innerShadow_20020_6772"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.717647 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_6772" result="effect3_innerShadow_20020_6772"/></filter><filter id="in86Zme" width="27.292" height="19.276" x="3.764" y="6.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6772" stdDeviation="1.25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palm-down-hand-light" /></template>
<style>
.akuw0fa9u {
  stop-color: var(--svg-color--bd8090, #BD8090);
}

.bi7un3blb {
  stop-color: var(--svg-color--b26b63, #B26B63);
}

.c0c3k_b5h {
  stop-color: var(--svg-color--f4bda1, #F4BDA1);
  stop-opacity: 0;
}

.e-3i2yrdu {
  stop-color: var(--svg-color--f4bda1, #F4BDA1);
}

.f6s0yqbjc {
  stop-color: var(--svg-color--b7798c, #B7798C);
  stop-opacity: 0;
}

.faw306w9s {
  stop-color: var(--svg-color--d59381, #D59381);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.iapxnjmkg {
  stop-color: var(--svg-color--ad6b5b, #AD6B5B);
}

.j2u72qbdb {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
}

.j2yizabta {
  stop-color: var(--svg-color--ad6b5b, #AD6B5B);
  stop-opacity: 0;
}

.jsjhui_2f {
  stop-color: var(--svg-color--b7798c, #B7798C);
}

.ksw6i0btb {
  stop-color: var(--svg-color--c88982, #C88982);
}

.ly115miad {
  stop-color: var(--svg-color--efb8a5, #EFB8A5);
}

.m0xlkr4wf {
  d: path("M12.766 16.73c0-1.7.886-2.574 2.398-3.078c.977-.211 4.531-.149 4.531-.149c1.133 0 1.78.448 2.438 1.055l3.758 3.21c.984.907 2.484 1.12 3.492.079c1.053-1.085.937-2.734-.344-3.844l-5.765-4.987c-1.3-1.17-1.922-1.818-4.31-1.818H9.993c-4.828-.029-7.777 2.93-7.777 6.805c0 2.344 2.082 4.807 3.684 6.469l1.718 1.633c1.362 1.207 3.133 2.226 4.977 2.226h1.828c.59 0 1.052-.058 1.79.383c.904.543 2.33.42 3.077-.328c.652-.652.85-1.587.504-2.444c-.601-1.497-2.262-2.126-3.879-2.439l-1.125-.156c-1.445-.102-2.023-1.734-2.023-2.616");
}

.nv8g0j1ga {
  stop-color: var(--svg-color--ad685d, #AD685D);
}

.o5weycjxj {
  stop-color: var(--svg-color--b46d68, #B46D68);
  stop-opacity: 0;
}

.q8ykaqean {
  stop-color: var(--svg-color--c78980, #C78980);
}

.sd4l66bbv {
  stop-color: var(--svg-color--bd8090, #BD8090);
  stop-opacity: 0;
}

.smfvy1b0j {
  stop-color: var(--svg-color--d59381, #D59381);
}

.t56sokbfc {
  stop-color: var(--svg-color--b46d68, #B46D68);
}

.t92xnb1cp {
  stop-color: var(--svg-color--b57b8f, #B57B8F);
  stop-opacity: 0;
}

.trlacabza {
  d: path("M24.034 20.596a2.19 2.19 0 0 1-2.552-1.753l-1.127-6.012l4.479.088l.953 5.124a2.193 2.193 0 0 1-1.753 2.553");
}

.tvg__8xpe {
  stop-color: var(--svg-color--ad685d, #AD685D);
  stop-opacity: 0;
}

.uxkm7obed {
  stop-color: var(--svg-color--bc7c7c, #BC7C7C);
}

.w3ph53b_n {
  d: path("M18.875 19.884a2.193 2.193 0 0 1-1.962-2.399l.52-5.185l4.357.437l-.52 5.185a2.186 2.186 0 0 1-2.395 1.962");
}

.y2u37pdke {
  stop-color: var(--svg-color--d79f98, #D79F98);
}

.ybn-7fb7j {
  fill: var(--svg-color--ffe5cb, #FFE5CB);
  d: path("m21.836 10.025l6.408 5.047a.821.821 0 0 1-.994 1.307l-5.917-4.337a2 2 0 0 0-1.424-.372l-4.645.566a4 4 0 0 0-3.517 3.97v.561a4 4 0 0 0 .962 2.601l.106.125a3 3 0 0 0 1.947 1.03l1.77.198a3 3 0 0 1 1.727.8l.789.744a.682.682 0 0 1-.905 1.02l-.391-.328a3 3 0 0 0-1.923-.697h-2.002a4 4 0 0 1-2.725-1.071L7.54 17.874a4 4 0 0 1-1.171-3.835l.18-.772a5 5 0 0 1 4.722-3.864l7.972-.234a4 4 0 0 1 2.593.856");
}

.z309z-5wr {
  stop-color: var(--svg-color--dba39e, #DBA39E);
}

.z4oifbcew {
  stop-color: var(--svg-color--b57b8f, #B57B8F);
}

.zlcirlb_i {
  d: path("M15.116 17.828a2.19 2.19 0 0 1-1.738-2.552l.94-5.121l4.268.8l-.942 5.12a2.17 2.17 0 0 1-2.528 1.753");
}

</style>
