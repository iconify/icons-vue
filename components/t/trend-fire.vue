<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_a2vebsm"/><path class="kts-heyxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trend-fire" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kts-heyxs {
  d: path("m8.75 17.5l2.5-2.5l1.5 1.5l2.75-2.75m-2 0h2.25V16");
}

.o_a2vebsm {
  d: path("M12 21.25a7 7 0 0 1-7-7c0-3.5 2-6 4-8c.25 1.5 1 2.5 2 3c.5-3 1.75-5 3.5-6.5c.25 2.5 1.5 4 2.5 5.5s2 3.5 2 6a7 7 0 0 1-7 7");
}

</style>
