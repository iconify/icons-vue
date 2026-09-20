<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rbwrj-biq"/><path class="dvxq3_bid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:serverless-outline-thin" /></template>
<style>
.dvxq3_bid {
  d: path("m14 10 -3.5 3.5H13L9.5 17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rbwrj-biq {
  d: path("M4 18a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 9a5.5 5.5 0 0 1 4.5 9Z");
}

</style>
