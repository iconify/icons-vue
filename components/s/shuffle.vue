<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es02i233b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:shuffle" /></template>
<style>
.es02i233b {
  fill: currentColor;
  d: path("M10.59 9.17L5.41 4L4 5.41l5.17 5.17zM14.5 4l2.04 2.04L4 18.59L5.41 20L17.96 7.46L20 9.5V4zm.33 9.41l-1.41 1.41l3.13 3.13L14.5 20H20v-5.5l-2.04 2.04z");
}

</style>
