<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iaymc3bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-circle-16-regular" /></template>
<style>
.iaymc3bsb {
  fill: currentColor;
  d: path("M3 8a5 5 0 1 1 10 0A5 5 0 0 1 3 8m5-6a6 6 0 1 0 0 12A6 6 0 0 0 8 2m0 7a1 1 0 1 0 0-2a1 1 0 0 0 0 2m4-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0M5 9a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
