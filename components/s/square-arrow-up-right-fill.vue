<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0doct3at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-up-right-fill" /></template>
<style>
.s0doct3at {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm14 8V9a1 1 0 0 0-1-1h-4a1 1 0 0 0 0 2h1.586l-4.293 4.293a.999.999 0 1 0 1.414 1.414L14 11.414V13a1 1 0 0 0 2 0");
}

</style>
