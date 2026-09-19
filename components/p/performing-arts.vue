<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i07fzNd)"><path fill="url(#imtIzYb)" clip-rule="evenodd" class="xb8mz88_e"/></g><path fill="url(#i49db7c)" clip-rule="evenodd" class="xb8mz88_e"/><path fill="url(#iyC58rb)" clip-rule="evenodd" class="xb8mz88_e"/><g filter="url(#iHgjtSc)"><path fill="url(#i9rZXQd)" clip-rule="evenodd" class="ud7wj-3uy"/></g><path fill="url(#iqbfTee)" clip-rule="evenodd" class="ud7wj-3uy"/><path fill="url(#iSpaQ1c)" clip-rule="evenodd" class="ud7wj-3uy"/><path fill="url(#ilOXnMh)" clip-rule="evenodd" class="ud7wj-3uy"/><defs><radialGradient id="i49db7c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53266 5.75048 -5.2486 -4.13706 29.72 12)" gradientUnits="userSpaceOnUse"><stop class="tpoaefbpl"/><stop offset="1" class="dggwlx_ey"/></radialGradient><radialGradient id="iyC58rb" cx="0" cy="0" r="1" gradientTransform="rotate(62.43 -5.063 20.231)scale(4.12717 5.71836)" gradientUnits="userSpaceOnUse"><stop class="p1n-jbb1o"/><stop offset="1" class="hl5msf20h"/></radialGradient><radialGradient id="iqbfTee" cx="0" cy="0" r="1" gradientTransform="matrix(-5.64255 5.1875 -5.82918 -6.34052 19 2.5)" gradientUnits="userSpaceOnUse"><stop class="jo1oymm8n"/><stop offset="1" class="i5vv_d6we"/></radialGradient><radialGradient id="iSpaQ1c" cx="0" cy="0" r="1" gradientTransform="matrix(2.91995 4.25 -5.45054 3.74478 2 2)" gradientUnits="userSpaceOnUse"><stop class="i3jrgpbbp"/><stop offset="1" class="yc3v_8bms"/></radialGradient><linearGradient id="imtIzYb" x1="14.42" x2="28.733" y1="22.687" y2="22.687" gradientUnits="userSpaceOnUse"><stop class="agd54wmtu"/><stop offset="1" class="ywjgcmb8r"/></linearGradient><linearGradient id="i9rZXQd" x1="5.994" x2="16.958" y1="11" y2="11" gradientUnits="userSpaceOnUse"><stop offset=".163" class="ylwjrbbrp"/><stop offset="1" class="xf8-6ebew"/></linearGradient><linearGradient id="ilOXnMh" x1="3.109" x2="3.546" y1="10.934" y2="10.864" gradientUnits="userSpaceOnUse"><stop class="g3vk8hiks"/><stop offset="1" class="zeqdto87n"/></linearGradient><filter id="i07fzNd" width="16.578" height="18.249" x="13.572" y="11.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.498039 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4196"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.631373 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4196" result="effect2_innerShadow_18_4196"/></filter><filter id="iHgjtSc" width="17.2" height="18.4" x="2" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.533333 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4196"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.592157 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4196" result="effect2_innerShadow_18_4196"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.458824 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_4196" result="effect3_innerShadow_18_4196"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:performing-arts" /></template>
<style>
.agd54wmtu {
  stop-color: var(--svg-color--f89552, #F89552);
}

.dggwlx_ey {
  stop-color: var(--svg-color--ffda4d, #FFDA4D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3vk8hiks {
  stop-color: var(--svg-color--3672e7, #3672E7);
}

.hl5msf20h {
  stop-color: var(--svg-color--dd9643, #DD9643);
  stop-opacity: 0;
}

.i3jrgpbbp {
  stop-color: var(--svg-color--287fda, #287FDA);
}

.i5vv_d6we {
  stop-color: var(--svg-color--68dbff, #68DBFF);
  stop-opacity: 0;
}

.jo1oymm8n {
  stop-color: var(--svg-color--68dbff, #68DBFF);
}

.p1n-jbb1o {
  stop-color: var(--svg-color--dd9643, #DD9643);
}

.tpoaefbpl {
  stop-color: var(--svg-color--ffda4d, #FFDA4D);
}

.ud7wj-3uy {
  fill-rule: evenodd;
  d: path("m14.445 2.908l1.756-.745c1.474-.624 3.048.634 2.766 2.205L17.21 14.373A6.815 6.815 0 0 1 10.499 20a6.815 6.815 0 0 1-6.712-5.627L2.031 4.368c-.273-1.57 1.302-2.829 2.776-2.205l1.766.745a10.08 10.08 0 0 0 7.872 0m-8.772 9.26c.933 1.453 2.744 2.443 4.827 2.443s3.895-.99 4.827-2.453c.174-.269.673-.176.673.139v.009c0 2.694-2.658 4.852-5.847 4.685c-2.669-.139-4.86-1.935-5.12-4.204A4 4 0 0 1 5 12.306c0-.315.499-.417.673-.139M8 9.121c.814 0 1.506.537 1.824 1.317c.037.095.159.074.168-.031c.01-.116.01-.221 0-.338c-.075-1.106-.879-2.002-1.87-2.065C6.963 7.92 6 8.964 6 10.25v.158c.01.105.13.126.178.031c.318-.78 1.01-1.317 1.823-1.317m6.815 1.317c-.318-.78-1.008-1.317-1.82-1.317c-.811 0-1.501.537-1.819 1.317c-.046.095-.168.074-.177-.031v-.158c0-1.286.96-2.33 2.127-2.245c.989.063 1.791.959 1.866 2.065q.015.177 0 .338c-.01.105-.14.126-.177.031");
}

.xb8mz88_e {
  fill-rule: evenodd;
  d: path("M13.572 17.449a5.25 5.25 0 0 0 3.22-4.844v-.023l.771.327a10.08 10.08 0 0 0 7.874 0l1.756-.745c1.474-.624 3.048.634 2.776 2.204l-1.756 10.005A6.815 6.815 0 0 1 21.5 30a6.815 6.815 0 0 1-6.713-5.627zm7.928 6.18c1.893 0 3.54 1.09 4.389 2.69c.157.305.611.193.611-.153c0-.173-.01-.346-.03-.53c-.236-2.495-2.228-4.47-4.654-4.624c-2.9-.183-5.316 2.19-5.316 5.154v.01c0 .346.454.448.611.153c.849-1.61 2.496-2.7 4.389-2.7m-.685-3.19c-.318-.78-1.01-1.317-1.823-1.317c-.814 0-1.506.537-1.814 1.317c-.047.095-.169.074-.178-.031v-.158c0-1.286.963-2.33 2.123-2.245c.991.063 1.795.959 1.87 2.066c.01.115.01.231 0 .337c-.01.105-.14.126-.178.031m3.197-1.317c.814 0 1.506.537 1.824 1.317c.037.095.168.074.178-.031c.01-.106.01-.222 0-.338c-.075-1.106-.88-2.002-1.87-2.065c-1.16-.085-2.123.959-2.123 2.245v.158c.01.105.13.126.177.031c.309-.78 1.001-1.317 1.814-1.317");
}

.xf8-6ebew {
  stop-color: var(--svg-color--66d1ff, #66D1FF);
}

.yc3v_8bms {
  stop-color: var(--svg-color--287fda, #287FDA);
  stop-opacity: 0;
}

.ylwjrbbrp {
  stop-color: var(--svg-color--3a8fff, #3A8FFF);
}

.ywjgcmb8r {
  stop-color: var(--svg-color--ffd350, #FFD350);
}

.zeqdto87n {
  stop-color: var(--svg-color--3672e7, #3672E7);
  stop-opacity: 0;
}

</style>
