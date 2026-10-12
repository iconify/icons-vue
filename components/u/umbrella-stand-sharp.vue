<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d66raww7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:umbrella-stand-sharp" /></template>
<style>
.d66raww7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 10.25v-7h-4v2.5m9 4.5v-7.5h4v2.5m-12.25 5h11.5l-1 10v1h-9.5v-1Zm.35 3.5h10.8");
}

</style>
