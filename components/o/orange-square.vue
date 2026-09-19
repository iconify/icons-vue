<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iKaWPSh)"><path fill="url(#ilCLsJd)" class="uxgsmd1pz"/></g><defs><linearGradient id="ilCLsJd" x1="16" x2="16" y1="2" y2="30" gradientUnits="userSpaceOnUse"><stop class="sgxv9w2bq"/><stop offset="1" class="plorv8k-q"/></linearGradient><filter id="iKaWPSh" width="29" height="28.75" x="1" y="1.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.160784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_3132"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.509804 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_3132" result="effect2_innerShadow_18590_3132"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:orange-square" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.plorv8k-q {
  stop-color: var(--svg-color--ee4247, #EE4247);
}

.sgxv9w2bq {
  stop-color: var(--svg-color--ff883f, #FF883F);
}

.uxgsmd1pz {
  d: path("M2 4a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2v24a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2z");
}

</style>
