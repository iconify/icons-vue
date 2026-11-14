<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca5hoybfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:presence-sensor" /></template>
<style>
.ca5hoybfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4.5h11a5.5 3.5 0 0 1-11 0Zm8.393 6.947a4.5 4.5 0 0 1-5.786 0m8.035 2.681a8 8 0 0 1-10.284 0m12.534 2.682a11.5 11.5 0 0 1-14.784 0");
}

</style>
