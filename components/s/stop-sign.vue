<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPQnhTd)"><path fill="url(#iWrFg4e)" class="e0nydq3bp"/><path fill="url(#ihxuVve)" class="e0nydq3bp"/></g><path fill="url(#iQsT1Wd)" class="yu8cbrbpr"/><defs><linearGradient id="iWrFg4e" x1="27.86" x2="8.851" y1="6.975" y2="27.592" gradientUnits="userSpaceOnUse"><stop class="tuo1lcc8n"/><stop offset=".501" class="nryaqqb2f"/><stop offset="1" class="quduj0bny"/></linearGradient><linearGradient id="ihxuVve" x1="16" x2="16" y1="31.578" y2="27.653" gradientUnits="userSpaceOnUse"><stop class="i57y7fvxj"/><stop offset="1" class="vsd6hzb8i"/></linearGradient><linearGradient id="iQsT1Wd" x1="29.118" x2="3.998" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="qeq05cbyv"/><stop offset="1" class="mxmv48b6z"/></linearGradient><filter id="iPQnhTd" width="28.75" height="28" x="2" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.513726 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12046"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:stop-sign" /></template>
<style>
.e0nydq3bp {
  d: path("M11.74 2h8.52c.99 0 1.93.39 2.63 1.09l6.02 6.02c.7.7 1.09 1.64 1.09 2.63v8.52c0 .99-.39 1.93-1.09 2.63l-6.02 6.02c-.7.7-1.64 1.09-2.63 1.09h-8.52c-.99 0-1.93-.39-2.63-1.09l-6.02-6.02c-.7-.7-1.09-1.64-1.09-2.63v-8.52c0-.99.39-1.93 1.09-2.63l6.02-6.02c.7-.7 1.64-1.09 2.63-1.09");
}

.ft5dv1b6b {
  fill: none;
}

.i57y7fvxj {
  stop-color: var(--svg-color--8c749b, #8C749B);
}

.mxmv48b6z {
  stop-color: var(--svg-color--cc307a, #CC307A);
}

.nryaqqb2f {
  stop-color: var(--svg-color--d5c9dd, #D5C9DD);
}

.qeq05cbyv {
  stop-color: var(--svg-color--e53146, #E53146);
}

.quduj0bny {
  stop-color: var(--svg-color--b9b3bc, #B9B3BC);
}

.tuo1lcc8n {
  stop-color: var(--svg-color--fbf9fc, #FBF9FC);
}

.vsd6hzb8i {
  stop-color: var(--svg-color--8c749b, #8C749B);
  stop-opacity: 0;
}

.yu8cbrbpr {
  d: path("M12.57 4h6.86c.99 0 1.93.39 2.63 1.09l4.85 4.85c.7.7 1.09 1.64 1.09 2.63v6.86c0 .99-.39 1.93-1.09 2.63l-4.85 4.85c-.7.7-1.64 1.09-2.63 1.09h-6.86c-.99 0-1.93-.39-2.63-1.09l-4.85-4.85c-.7-.7-1.09-1.64-1.09-2.63v-6.86c0-.99.39-1.93 1.09-2.63l4.85-4.85c.7-.7 1.64-1.09 2.63-1.09");
}

</style>
