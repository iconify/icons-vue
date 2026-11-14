<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qeb8j6bgh"/><path class="c-hk4gbqv"/><path class="g18zu8bnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:periodicals" /></template>
<style>
.c-hk4gbqv {
  d: path("M11.625 5h5.75A2.625 2.625 0 0 1 20 7.625v11.25a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 9 18.875V7.625A2.625 2.625 0 0 1 11.625 5m.125 3.5h5.5");
}

.g18zu8bnm {
  d: path("M13.25 11.5h2.5a1.5 1.5 0 0 1 1.5 1.5v3.5a1.5 1.5 0 0 1-1.5 1.5h-2.5a1.5 1.5 0 0 1-1.5-1.5V13a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qeb8j6bgh {
  d: path("m8.75 21.5l-4-16l10.5-2.75l.5 2.25");
}

</style>
