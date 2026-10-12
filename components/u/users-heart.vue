<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rknchmb5r"/><path class="x_ue7kabl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:users-heart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rknchmb5r {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

.x_ue7kabl {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75m14-6c-.2 0-.4-.07-.55-.2c-1.3-1.15-2.7-2.35-2.7-4c0-1 .75-1.8 1.7-1.8c.65 0 1.2.35 1.55.9c.35-.55.9-.9 1.55-.9c.95 0 1.7.8 1.7 1.8c0 1.65-1.4 2.85-2.7 4c-.15.13-.35.2-.55.2");
}

</style>
