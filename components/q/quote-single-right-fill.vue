<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7yirob2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:quote-single-right-fill" /></template>
<style>
.j7yirob2l {
  fill: currentColor;
  d: path("M14 12V9a.997.997 0 0 0-1-1h-2a.997.997 0 0 0-1 1v2a.997.997 0 0 0 1 1Zm2 1c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 11 18a1 1 0 0 1 0-2c1.27 0 2.405-.804 2.83-2H11a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3Z");
}

</style>
