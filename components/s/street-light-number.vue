<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="etjwxybfj"/><path class="dm5l9u09u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:street-light-number" /></template>
<style>
.dm5l9u09u {
  d: path("M14.016 3h3.968A1.17 1.17 0 0 1 19 4.75l-.568.994a1.5 1.5 0 0 1-1.302.756h-2.26a1.5 1.5 0 0 1-1.302-.756L13 4.75A1.17 1.17 0 0 1 14.016 3M16.5 16.5l2-1.5v6.5m-2 0h4");
}

.etjwxybfj {
  d: path("M4 21.5h6m-3 0V9a6 6 0 0 1 6-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
