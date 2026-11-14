<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpjthqb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:prairie" /></template>
<style>
.wpjthqb5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20h19M6 20l-2.5-6M6 20v-8.5M6 20l2.5-6m6.5 6l-2.5-6m2.5 6v-9m0 9l2.5-6M16 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
