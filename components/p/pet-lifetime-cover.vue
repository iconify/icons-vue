<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf55yccke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-lifetime-cover" /></template>
<style>
.nf55yccke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.337 16.252a8.6 8.6 0 0 1-2.087.248c-4 0-6.75-2.5-6.75-6V3L8 6.25h4.5L17 3v7.5c0 1.596-.572 2.984-1.573 4.021M7.75 10.5h.01m4.99 0h.01M18 19c-1.25-2.25-3.5-2.25-3.5 0s2.25 2.25 3.5 0s3.5-2.25 3.5 0s-2.25 2.25-3.5 0Z");
}

</style>
