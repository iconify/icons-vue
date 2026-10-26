<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="gd0tn5bbt"/><path class="gyzfxxbyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:router-fill" /></template>
<style>
.gd0tn5bbt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 11L20 11C21.6569 11 23 12.3431 23 14L23 18C23 19.6569 21.6569 21 20 21L4 21C2.3431 21 1 19.6569 1 18L1 14C1 12.3431 2.3431 11 4 11ZM9 16C9 15.4477 8.5523 15 8 15C7.4477 15 7 15.4477 7 16C7 16.5523 7.4477 17 8 17C8.5523 17 9 16.5523 9 16ZM13 16C13 15.4477 12.5523 15 12 15C11.4477 15 11 15.4477 11 16C11 16.5523 11.4477 17 12 17C12.5523 17 13 16.5523 13 16ZM17 16C17 15.4477 16.5523 15 16 15C15.4477 15 15 15.4477 15 16C15 16.5523 15.4477 17 16 17C16.5523 17 17 16.5523 17 16Z");
  stroke: none;
}

.gyzfxxbyf {
  d: path("M7 12L5 4M17 12L19 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
