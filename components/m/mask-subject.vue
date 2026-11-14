<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_ys8bcdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mask-subject" /></template>
<style>
.l_ys8bcdn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 8.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M8 17.25c0-1.75 1.75-3 4-3s4 1.25 4 3ZM21.5 12a9.5 9.5 0 0 1-.75 3.75m-2 3a9.5 9.5 0 0 1-3 2M12 21.5a9.5 9.5 0 0 1-3.75-.75m-3-2a9.5 9.5 0 0 1-2-3M2.5 12a9.5 9.5 0 0 1 .75-3.75m2-3a9.5 9.5 0 0 1 3-2M12 2.5a9.5 9.5 0 0 1 3.75.75m3 2a9.5 9.5 0 0 1 2 3");
}

</style>
