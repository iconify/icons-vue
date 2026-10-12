<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa727gb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parachute-sharp" /></template>
<style>
.qa727gb9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.25a9.25 8.5 0 0 1 18.5 0c-1.5-1.25-3.1-1.25-4.6 0c-1.5-1.25-3.1-1.25-4.65 0c-1.5-1.25-3.1-1.25-4.6 0c-1.5-1.25-3.1-1.25-4.65 0Zm0 0l7.5 6.5m11-6.5l-7.5 6.5M12 11.25v6.5m-2.25 0h4.5v3.5h-4.5z");
}

</style>
