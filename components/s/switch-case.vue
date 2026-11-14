<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l1azzd74z"/><path class="etatracfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:switch-case" /></template>
<style>
.etatracfm {
  d: path("m18 3l2 2l-2 2m0 3l2 2l-2 2m0 3l2 2l-2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l1azzd74z {
  d: path("M2.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0H20M9 12c3 0 3-7 6-7h5M9 12c3 0 3 7 6 7h5");
}

</style>
