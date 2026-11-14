<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfh63ebgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:measure-depth" /></template>
<style>
.wfh63ebgd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6C4 4 5.75 4 7.25 6S10.5 8 12 6s3.25-2 4.75 0S20 8 21.5 6M12 2.5V21m0-10.5h3m-3 3h2m-2 3h2.5m-4.25 2.75L12 21l1.75-1.75");
}

</style>
