<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy7sb_15p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-right-open-fill" /></template>
<style>
.cy7sb_15p {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm11-1H6a.997.997 0 0 0-1 1v12a1 1 0 0 0 1 1h8Zm-2.293 4.707L9.414 12l2.293 2.293a.999.999 0 1 1-1.414 1.414l-3-3a.997.997 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414");
}

</style>
