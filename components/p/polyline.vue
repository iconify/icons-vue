<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unpkjebwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:polyline" /></template>
<style>
.unpkjebwa {
  fill: currentColor;
  d: path("M15 22v-2.5L8 16H3v-6h4.3L10 6.9V2h6v6h-4.3L9 11.1v3.15l6 3V16h6v6z");
}

</style>
