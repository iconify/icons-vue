<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qnt_uubje"/><path class="ic_pehd5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:underline-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.qnt_uubje {
  d: path("M5 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

</style>
