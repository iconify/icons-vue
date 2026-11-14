<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-12p8z7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:profile-birthday" /></template>
<style>
.q-12p8z7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 14h12.75A2.625 2.625 0 0 1 21 16.625v2.25a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-2.25A2.625 2.625 0 0 1 5.625 14m3-5.5h6.75A2.625 2.625 0 0 1 18 11.125v.25A2.625 2.625 0 0 1 15.375 14h-6.75A2.625 2.625 0 0 1 6 11.375v-.25A2.625 2.625 0 0 1 8.625 8.5M12 5.5v3m0-6h.01");
}

</style>
