<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k1rk9abnh"/><path class="l5yjw_ein"/><path class="tuqke_bmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sql-query" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k1rk9abnh {
  d: path("M3.5 5.5a6.5 2.5 0 1 0 13 0a6.5 2.5 0 1 0-13 0");
}

.l5yjw_ein {
  d: path("M3.5 5.5V16c0 1.4 2.9 2.5 6.5 2.5c.903 0 1.762-.069 2.542-.195m3.958-5.778V5.5");
}

.tuqke_bmh {
  d: path("M3.5 11c0 1.4 2.9 2.5 6.5 2.5s6.5-1.1 6.5-2.5m-1.25 6.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
