<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqoe2d5mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-close-fill" /></template>
<style>
.cqoe2d5mz {
  fill: currentColor;
  d: path("M17 5h3a1 1 0 0 1 0 2h-1v12a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3V7H4a1 1 0 0 1 0-2h3a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3m-3-1h-4a.997.997 0 0 0-1 1h6a.997.997 0 0 0-1-1m-2 8.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414L10.586 14l-1.293 1.293a.999.999 0 1 0 1.414 1.414L12 15.414l1.293 1.293a.999.999 0 1 0 1.414-1.414L13.414 14l1.293-1.293a.999.999 0 1 0-1.414-1.414Z");
}

</style>
