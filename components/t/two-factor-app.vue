<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="otft43bjg"/><path class="f_tq34bqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:two-factor-app" /></template>
<style>
.f_tq34bqb {
  d: path("M8.75 11.5h6.5V17h-6.5Zm1.5 0v-2a1.75 1.75 0 0 1 3.5 0v2");
}

.otft43bjg {
  d: path("M6 2h12v20H6Zm4.5 2.75h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
