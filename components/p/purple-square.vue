<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFjFF5n)"><path fill="url(#imGETQb)" class="uxgsmd1pz"/></g><defs><linearGradient id="imGETQb" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="eax-5zbjg"/><stop offset="1" class="bjylg5bpj"/></linearGradient><filter id="iFjFF5n" width="30" height="29" x="1" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.192157 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3220"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.384314 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3220" result="effect2_innerShadow_18590_3220"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.235294 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_3220" result="effect3_innerShadow_18590_3220"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:purple-square" /></template>
<style>
.bjylg5bpj {
  stop-color: var(--svg-color--664bb5, #664BB5);
}

.eax-5zbjg {
  stop-color: var(--svg-color--7c47c1, #7C47C1);
}

.ft5dv1b6b {
  fill: none;
}

.uxgsmd1pz {
  d: path("M2 4a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2v24a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2z");
}

</style>
