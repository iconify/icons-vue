<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ruenkpbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:not-superset-of-bold" /></template>
<style>
.ruenkpbmk {
  fill: currentColor;
  d: path("M208 188H89.67l14.55-16H152a68 68 0 0 0 52.86-110.71l12-13.22a12 12 0 0 0-17.76-16.14l-12.4 13.63A67.6 67.6 0 0 0 152 36H56a12 12 0 0 0 0 24h96a43.7 43.7 0 0 1 18.06 3.89L93.6 148H56a12 12 0 0 0 0 24h15.78l-32.66 35.93a12 12 0 1 0 17.76 16.14l11-12.07H208a12 12 0 0 0 0-24M188.44 79.36A44 44 0 0 1 152 148h-26Z");
}

</style>
