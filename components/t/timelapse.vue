<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="voincubod"/><path class="des5jubpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:timelapse" /></template>
<style>
.des5jubpl {
  d: path("m4.25 3l3 .75l-.75 3M12 7v5l3.5 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.voincubod {
  d: path("M12 2.5a9.5 9.5 0 1 1-4.75 1.25");
}

</style>
