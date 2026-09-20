<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3jkn35cv"/><path class="yea3zvbmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:verified-badge-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s3jkn35cv {
  d: path("M9 4h6l5 5v6l-5 5H9l-5 -5V9Z");
}

.yea3zvbmx {
  d: path("m8 12 3 3 5 -5");
}

</style>
