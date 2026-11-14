<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueid51eer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:neighborhood" /></template>
<style>
.ueid51eer {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5v-9l3.75-3.75L10 12.5v9m.25-12.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 2.5V21.5m3.25 0v-9h5.5v9m-19 0h19M6.25 16h.01m12.49-.5h.01m-.01 3h.01");
}

</style>
