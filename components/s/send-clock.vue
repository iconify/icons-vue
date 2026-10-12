<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtrxpieyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:send-clock" /></template>
<style>
.wtrxpieyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.82 3.61L4.18 9.64q-.93.36-.01.76l5.66 2.45q.92.4 1.32 1.32l2.45 5.66q.4.92.76-.01l6.03-15.64q.36-.93-.57-.57m-9.07 9.64L15 9");
}

</style>
