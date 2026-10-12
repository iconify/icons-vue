<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bpt8-n4_z"/><path class="hm6ht6b6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:u-turn-left" /></template>
<style>
.bpt8-n4_z {
  d: path("M3.75 18.5h11a4.75 4.75 0 0 0 0-9.5H4.25");
}

.hm6ht6b6s {
  d: path("M7.75 12.5L4.25 9l3.5-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
