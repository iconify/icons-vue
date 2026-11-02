<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k68rg0btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mountain-fill" /></template>
<style>
.k68rg0btn {
  fill: currentColor;
  d: path("M8.106 6.553a2.116 2.116 0 0 1 3.788 0l1 2c.02.04.061.065.106.065a.12.12 0 0 0 .106-.065a2.11 2.11 0 0 1 2.495-1.083a2.1 2.1 0 0 1 1.293 1.083l4 8c.181.356.274.75.273 1.149C21.164 18.924 20.265 20 19 20H5c-1.265 0-2.164-1.076-2.167-2.298a2.5 2.5 0 0 1 .273-1.149Z");
}

</style>
