<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v56t-0bsl"/><path class="q9fjk-j9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-age-limit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q9fjk-j9z {
  d: path("M13 3.75c2.75 1 3.75 4.75 2.5 7.75C14 11.5 13 9 13 3.75M9.5 8h.01m7.24 7.5h2.5A1.75 1.75 0 0 1 21 17.25v2.25a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.5v-2.25a1.75 1.75 0 0 1 1.75-1.75M15 17.75h6m-4.25-3.25V16m2.5-1.5V16");
}

.v56t-0bsl {
  d: path("M13.468 14.088c-1.819.15-3.601-1.177-4.968-2.088l-4.5.25c-1 0-1.5-.75-1.5-1.75S3 9 3.5 8.75l4-1.25c.5-2.5 2.5-4 5-4c3 0 5 2.25 5 5.5c0 1.036-.258 1.943-.702 2.704");
}

</style>
