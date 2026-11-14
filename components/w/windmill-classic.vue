<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nbqel6etg"/><path class="dpwl4tbld"/><path class="v-e_nsbpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:windmill-classic" /></template>
<style>
.dpwl4tbld {
  d: path("m11 12l-4 9.5h10L13 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbqel6etg {
  d: path("M17.303 3.447za1.5 1.5 0 0 1 0 2.121l-2.121 2.121a1.5 1.5 0 0 0 0 2.122l2.121 2.121a1.5 1.5 0 0 1 0 2.121a1.5 1.5 0 0 1-2.121 0l-2.121-2.121a1.5 1.5 0 0 0-2.122 0l-2.121 2.121a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l2.121-2.121a1.5 1.5 0 0 0 0-2.122L6.697 5.568a1.5 1.5 0 0 1 0-2.121a1.5 1.5 0 0 1 2.121 0l2.121 2.121a1.5 1.5 0 0 0 2.122 0l2.121-2.121a1.5 1.5 0 0 1 2.121 0");
}

.v-e_nsbpd {
  d: path("M10.75 21.5v-2.75a1.25 1.25 0 0 1 2.5 0v2.75");
}

</style>
