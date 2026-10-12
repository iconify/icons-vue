<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8jnq2bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wilted-flower" /></template>
<style>
.t8jnq2bua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 16V9.5C11 6.75 12.75 5 15 5s3.75 1.75 3.5 4.25m0 0C20.75 10 21.5 12 20 14c-2-.75-2.75-2.75-1.5-4.75M11 10c-2.25-.25-4 .75-4.75 3c2.25.25 4-.75 4.75-3m-5.5 6h11l-1.15 4.35a1.25 1.25 0 0 1-1.2.9h-6.3a1.25 1.25 0 0 1-1.2-.9Z");
}

</style>
