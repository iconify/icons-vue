<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s8yit4btn"/><path class="a1gqybcqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:training-workshop" /></template>
<style>
.a1gqybcqm {
  d: path("m5.5 11l3-3L11 9.5L13.5 6m6.25 3zA1.25 1.25 0 0 1 21 10.25v5.5A1.25 1.25 0 0 1 19.75 17a1.25 1.25 0 0 1-1.25-1.25v-5.5A1.25 1.25 0 0 1 19.75 9m0 8za.736.736 0 0 1 .643 1.093l-.018.032a.715.715 0 0 1-1.25 0l-.018-.032A.736.736 0 0 1 19.75 17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s8yit4btn {
  d: path("M4.75 3h9.5A1.75 1.75 0 0 1 16 4.75v7.5A1.75 1.75 0 0 1 14.25 14h-9.5A1.75 1.75 0 0 1 3 12.25v-7.5A1.75 1.75 0 0 1 4.75 3M6.5 14l-2 7.5m8-7.5l2 7.5");
}

</style>
