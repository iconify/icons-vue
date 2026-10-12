<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wdhzekbjy"/><path class="pudm9gbfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:medical-record-search" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pudm9gbfd {
  d: path("M11.5 10.5h1q.4 0 .4.4v1.05q0 .4.4.4h1.05q.4 0 .4.4v1q0 .4-.4.4H13.3q-.4 0-.4.4v1.05q0 .4-.4.4h-1q-.4 0-.4-.4v-1.05q0-.4-.4-.4H9.65q-.4 0-.4-.4v-1q0-.4.4-.4h1.05q.4 0 .4-.4V10.9q0-.4.4-.4");
}

.wdhzekbjy {
  d: path("M2.75 6.25a2 2 0 0 1 2-2h4.5l2 2.25h8a2 2 0 0 1 2 2v10.75a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2Z");
}

</style>
