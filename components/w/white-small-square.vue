<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i61Lfqe)"><path fill="url(#ibV0GTh)" class="f1rc-wjcp"/></g><path fill="url(#iAyFZEe)" class="f1rc-wjcp"/><defs><linearGradient id="ibV0GTh" x1="16.336" x2="16.336" y1="12.375" y2="20.493" gradientUnits="userSpaceOnUse"><stop class="u6mwecb0a"/><stop offset="1" class="fyzrvbbun"/></linearGradient><linearGradient id="iAyFZEe" x1="21.688" x2="19.823" y1="11.688" y2="11.928" gradientUnits="userSpaceOnUse"><stop class="e1bcozb5y"/><stop offset="1" class="kv3-46-0j"/></linearGradient><filter id="i61Lfqe" width="11.485" height="11.235" x="10.594" y="10.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.996078 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2870"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.756863 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2870" result="effect2_innerShadow_18590_2870"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.952941 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_2870" result="effect3_innerShadow_18590_2870"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.439216 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18590_2870" result="effect4_innerShadow_18590_2870"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:white-small-square" /></template>
<style>
.e1bcozb5y {
  stop-color: var(--svg-color--e8e8e8, #E8E8E8);
}

.f1rc-wjcp {
  d: path("M11.344 11.22c0-.393.32-.713.713-.713h8.559c.394 0 .713.32.713.714v8.558c0 .394-.32.714-.713.714h-8.559a.713.713 0 0 1-.713-.714z");
}

.ft5dv1b6b {
  fill: none;
}

.fyzrvbbun {
  stop-color: var(--svg-color--bba4d2, #BBA4D2);
}

.kv3-46-0j {
  stop-color: var(--svg-color--e8e8e8, #E8E8E8);
  stop-opacity: 0;
}

.u6mwecb0a {
  stop-color: var(--svg-color--f6e8ff, #F6E8FF);
}

</style>
