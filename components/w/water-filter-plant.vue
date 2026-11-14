<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stdrkgqby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-filter-plant" /></template>
<style>
.stdrkgqby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h18V5l-6.5 6v2.5h-5V11L3 5ZM6.5 8h11M12 16.5s-2.5 2-2.5 3a2.5 2.5 0 0 0 5 0c0-1-2.5-3-2.5-3");
}

</style>
