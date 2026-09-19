<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaz_h0blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-arrow-circle-right" /></template>
<style>
.xaz_h0blf {
  fill: currentColor;
  d: path("M22 12c0-5.52-4.48-10-10-10S2 6.48 2 12s4.48 10 10 10s10-4.48 10-10M4 12c0-4.42 3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8s-8-3.58-8-8m12 0l-4 4l-1.41-1.41L12.17 13H8v-2h4.17l-1.59-1.59L12 8z");
}

</style>
