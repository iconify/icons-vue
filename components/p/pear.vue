<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9ghalbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pear" /></template>
<style>
.y9ghalbpo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6c2 0 2.5 2 2.5 3.5s3.5 3 3.5 6.5c0 3-3 5-6 5s-6-2-6-5c0-3.5 3.5-5 3.5-6.5S10 6 12 6m0 0c0-1.5.5-2.5 2-3");
}

</style>
