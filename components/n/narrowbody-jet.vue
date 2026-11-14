<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csyumd4tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:narrowbody-jet" /></template>
<style>
.csyumd4tq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c1.25 0 1.5 1.5 1.5 2.5v4.5l7.5 5v2L13.5 14v4.5l2.5 2v1l-4-1l-4 1v-1l2.5-2V14L3 16.5v-2l7.5-5V5c0-1 .25-2.5 1.5-2.5M7 9.75v3m10-3v3");
}

</style>
