<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fpxnec3eu"/><path class="kn8pwsbsj"/><path class="yheiu4i6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:orange-tree" /></template>
<style>
.fpxnec3eu {
  d: path("M4.5 9.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0M12 17v4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kn8pwsbsj {
  fill: currentColor;
  d: path("M8.25 7.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5.5 1.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-4 4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.yheiu4i6w {
  d: path("M8.5 21.5h7");
}

</style>
