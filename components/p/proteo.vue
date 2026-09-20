<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y7eb2b0iq"/><path fill="url(#SVGh77ljdPX)" class="rknj1wb5g"/><defs><linearGradient id="SVGh77ljdPX" x1="12" x2="12" y1="7.026" y2="18.869" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".68" class="stui2mbih"/><stop offset="1" class="d-llkv2cb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:proteo" /></template>
<style>
.d-llkv2cb {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.5;
}

.ft5dv1b6b {
  fill: none;
}

.rknj1wb5g {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("m10.096 5.861l-3.78 5.665L12 21l5.684-9.474l-3.78-5.665l1.118 5.665h1.331l-3.88 7.106v-7.106h1.218L12.02 3.024L12 3l-.019.024l-1.672 8.502h1.217v7.106l-3.884-7.106h1.336z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.y7eb2b0iq {
  fill: var(--svg-color--d7a012, #d7a012);
  d: path("m10.096 5.861l-3.78 5.665L12 21l5.684-9.474l-3.78-5.665l1.118 5.665h1.331l-3.88 7.106v-7.106h1.218L12.02 3.024L12 3l-.019.024l-1.672 8.502h1.217v7.106l-3.884-7.106h1.336z");
}

</style>
