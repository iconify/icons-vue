<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2z5djaex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:socket-wrench" /></template>
<style>
.j2z5djaex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.825 14.297l-6.249 6.249a1.5 1.5 0 0 1-2.122-2.122l6.249-6.249a3.5 3.5 0 0 1 3.912-4.618l2.828 2.828a3.5 3.5 0 0 1-4.618 3.912M14.15 7.03l2.56-2.57q.53-.53 1.06 0l1.77 1.77q.53.53 0 1.06l-2.57 2.56q-.53.53-1.06 0l-1.76-1.76q-.53-.53 0-1.06");
}

</style>
