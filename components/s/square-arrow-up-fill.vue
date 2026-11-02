<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6qfbbwff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-up-fill" /></template>
<style>
.d6qfbbwff {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm12.293 6.707a.999.999 0 1 0 1.414-1.414l-3-3a.997.997 0 0 0-1.414 0l-3 3a.999.999 0 1 0 1.414 1.414L11 10.414V16a1 1 0 0 0 2 0v-5.586Z");
}

</style>
