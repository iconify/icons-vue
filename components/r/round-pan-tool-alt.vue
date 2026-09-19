<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpd4xzu2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-pan-tool-alt" /></template>
<style>
.bpd4xzu2b {
  fill: currentColor;
  d: path("M5.2 15.43c0-.65.6-1.13 1.24-.99l3.56.8V4.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v6h.91c.31 0 .62.07.89.21l4.09 2.04c.77.38 1.21 1.22 1.09 2.07l-.63 4.46c-.14.99-.99 1.72-1.98 1.72h-6.16c-.53 0-1.29-.21-1.66-.59l-4.07-4.29a.98.98 0 0 1-.28-.69");
}

</style>
