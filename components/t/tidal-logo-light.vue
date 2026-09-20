<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vulih5txa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tidal-logo-light" /></template>
<style>
.vulih5txa {
  fill: currentColor;
  d: path("m252.24 91.76l-40-40a6 6 0 0 0-8.48 0L168 87.52l-35.76-35.76a6 6 0 0 0-8.48 0L88 87.52L52.24 51.76a6 6 0 0 0-8.48 0l-40 40a6 6 0 0 0 0 8.48l40 40a6 6 0 0 0 8.48 0L88 104.48L119.52 136l-35.76 35.76a6 6 0 0 0 0 8.48l40 40a6 6 0 0 0 8.48 0l40-40a6 6 0 0 0 0-8.48L136.48 136L168 104.48l35.76 35.76a6 6 0 0 0 8.48 0l40-40a6 6 0 0 0 0-8.48M48 127.51L16.49 96L48 64.49L79.51 96Zm80 80L96.49 176L128 144.49L159.51 176Zm0-80L96.49 96L128 64.49L159.51 96Zm80 0L176.49 96L208 64.49L239.51 96Z");
}

</style>
