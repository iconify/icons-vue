<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k56qupbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-minus-corner-fill" /></template>
<style>
.k56qupbvl {
  fill: currentColor;
  d: path("M21 9H4v9a1 1 0 0 0 1 1h3a1 1 0 0 1 0 2H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1m-8 6h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
