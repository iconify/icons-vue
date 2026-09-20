<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gveijgajs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:power-plug-outline-sharp" /></template>
<style>
.gveijgajs {
  fill: currentColor;
  d: path("M11.5 19h1v-1.85l3.5-3.5V9H8v4.65l3.5 3.5zm-2 2v-3L6 14.5V7h2V3h2v4h4V3h2v4h2v7.5L14.5 18v3zm2.5-7");
}

</style>
