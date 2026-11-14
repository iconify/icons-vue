<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br34yg9gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snowflake-schema" /></template>
<style>
.br34yg9gk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 9.5h1a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 11.5 9.5M9.75 12h-2m6.5 0h2m-10.5-2h.5a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5m12 0h.5a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5M6 10V7.5M6 14v2.5M18 10V7.5m0 6.5v2.5M6 4.5za1.25 1.25 0 0 1 1.25 1.25v.5A1.25 1.25 0 0 1 6 7.5a1.25 1.25 0 0 1-1.25-1.25v-.5A1.25 1.25 0 0 1 6 4.5m0 12za1.25 1.25 0 0 1 1.25 1.25v.5A1.25 1.25 0 0 1 6 19.5a1.25 1.25 0 0 1-1.25-1.25v-.5A1.25 1.25 0 0 1 6 16.5m12-12za1.25 1.25 0 0 1 1.25 1.25v.5A1.25 1.25 0 0 1 18 7.5a1.25 1.25 0 0 1-1.25-1.25v-.5A1.25 1.25 0 0 1 18 4.5m0 12za1.25 1.25 0 0 1 1.25 1.25v.5A1.25 1.25 0 0 1 18 19.5a1.25 1.25 0 0 1-1.25-1.25v-.5A1.25 1.25 0 0 1 18 16.5");
}

</style>
