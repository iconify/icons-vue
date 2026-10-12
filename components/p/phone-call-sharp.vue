<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thrc-33fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phone-call-sharp" /></template>
<style>
.thrc-33fy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.6 3.25h2.6l.72-.002l.23.682l1.1 3.3l.19.587l-.44.433l-1.6 1.6a12.5 12.5 0 0 0 5.75 5.75l1.6-1.6l.433-.44l.587.19l3.3 1.1l.682.23l-.002.72v4.95H18.4c-8.3 0-15.15-6.85-15.15-15.15V3.25zm8.9.5a6 6 0 0 1 5.75 5.75M14.5 7l2.299.201L17 9.5");
}

</style>
