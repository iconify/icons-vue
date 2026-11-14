<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_hl_5i2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:press-room" /></template>
<style>
.o_hl_5i2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5h19m-17 0v8m15-8v8m-15-8V3h4L11 5.5v8m5.707-10.769l2.898.776a1.5 1.5 0 0 1 1.06 1.838L19.63 9.208a1.5 1.5 0 0 1-1.837 1.061l-2.898-.776a1.5 1.5 0 0 1-1.06-1.838l1.035-3.863a1.5 1.5 0 0 1 1.837-1.061");
}

</style>
