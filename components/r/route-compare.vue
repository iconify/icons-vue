<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o-j74ecin"/><path class="s1mp3z1kv"/><path class="t2f0tsimh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:route-compare" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o-j74ecin {
  d: path("M9.5 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.s1mp3z1kv {
  d: path("M12 16.5c0-4.5-6-5-6-13m6 13c0-4.5 6-5 6-13");
}

.t2f0tsimh {
  d: path("M3.5 6L6 3.5L8.5 6m7 0L18 3.5L20.5 6");
}

</style>
