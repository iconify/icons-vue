<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fj87c9bsl"/><path class="xcnkrebpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seasons-cycle" /></template>
<style>
.fj87c9bsl {
  d: path("M12 4.5a8 8 0 1 0 7 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xcnkrebpi {
  d: path("m10 2.5l2 2l-2 2m-1 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
