<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od0bhb3en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mouse-wireless" /></template>
<style>
.od0bhb3en {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 8za5.25 5.25 0 0 1 5.25 5.25v3a5.25 5.25 0 0 1-5.25 5.25A5.25 5.25 0 0 1 4 16.25v-3A5.25 5.25 0 0 1 9.25 8m0 3v2M13 5a4 4 0 0 1 4 4m-4-7a7 7 0 0 1 7 7");
}

</style>
