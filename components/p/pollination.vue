<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="da-r0xtqg"/><path class="q4zxaj40b"/><path class="ejm6de9yf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pollination" /></template>
<style>
.da-r0xtqg {
  d: path("m8.308 12.388l.323.554a2.2 2.2 0 0 0 1.428 1.037l.627.136a.935.935 0 0 1 .499 1.537l-.427.479a2.2 2.2 0 0 0-.545 1.678l.064.638a.935.935 0 0 1-1.308.951l-.587-.259a2.2 2.2 0 0 0-1.764 0l-.587.259a.935.935 0 0 1-1.308-.951l.064-.638a2.2 2.2 0 0 0-.545-1.678l-.427-.479a.935.935 0 0 1 .499-1.537l.627-.136a2.2 2.2 0 0 0 1.428-1.037l.323-.554a.935.935 0 0 1 1.616 0M15 4a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.ejm6de9yf {
  d: path("M10.75 6a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0m6.75 0a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0m-2-3l-.75-.75m2 .75l.75-.75M13.75 8h4.75M14 9.75h4.25M7.5 16h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q4zxaj40b {
  d: path("M13.5 8.5a2.5 3.5 0 1 0 5 0a2.5 3.5 0 1 0-5 0");
}

</style>
