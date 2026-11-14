<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ejjvp9bit"/><path class="ityt4eb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wash-by-hand" /></template>
<style>
.ejjvp9bit {
  d: path("M3 13.25h18l-2 6a2.25 2.25 0 0 1-2.25 2.25h-9.5A2.25 2.25 0 0 1 5 19.25ZM9 3L5 5l1.5 3L8 7.5v3h8v-3l1.5.5L19 5l-4-2q-3 2-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ityt4eb3g {
  d: path("M6.5 17q2.75-1.5 5.5 0t5.5 0");
}

</style>
