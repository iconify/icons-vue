<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn9smw17t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:search-fill" /></template>
<style>
.pn9smw17t {
  fill: currentColor;
  d: path("m16.321 14.906l5.386 5.387a.999.999 0 1 1-1.414 1.414l-5.387-5.386A8.002 8.002 0 0 1 4.343 4.343a8 8 0 0 1 11.978 10.563");
}

</style>
