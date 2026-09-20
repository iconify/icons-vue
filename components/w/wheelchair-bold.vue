<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="eoy7ebcdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wheelchair-bold" /></template>
<style>
.eoy7ebcdz {
  fill: currentColor;
  d: path("M255.14 187.54a12 12 0 0 0-15.6-6.68l-9.75 3.9l-27.06-54.13A12 12 0 0 0 192 124h-76v-16h52a12 12 0 0 0 0-24h-52v-6.19a34 34 0 1 0-24 0v8.88a76 76 0 1 0 88.35 106.57a12 12 0 1 0-21.57-10.52A52 52 0 1 1 92 112v24a12 12 0 0 0 12 12h80.58l28.68 57.37a12 12 0 0 0 15.19 5.77l20-8a12 12 0 0 0 6.69-15.6M104 36a10 10 0 1 1-10 10a10 10 0 0 1 10-10");
}

</style>
