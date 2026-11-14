<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu7l26qng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:metric-big-number" /></template>
<style>
.hu7l26qng {
  fill: currentColor;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.5h2.5V13h1.25v2.25H10.5v5.25H8v-5.25H2.5V13Zm0 4.75L5.25 13H8Zm6 0a3.75 3.75 0 0 1 7.5 0c0 4.25-4.25 6.25-4.75 9.75h4.75v2.5H14V19c0-4.5 5-6.5 5-10.75a1.25 1.25 0 0 0-2.5 0Z");
}

</style>
