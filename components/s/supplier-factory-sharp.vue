<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t96c8rowf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:supplier-factory-sharp" /></template>
<style>
.t96c8rowf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25V11.4l-.005-.896l.765.466l3.62 2.28V11.4l-.005-.896l.765.466l3.61 2.28v-10h3v18H2.75zm2.25-3h2m2.25 0h2m5.5-1.5h4.5v5.5h-4.5zm2.25 0v1.75");
}

</style>
