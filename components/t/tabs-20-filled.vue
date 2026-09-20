<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wa8wj64_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tabs-20-filled" /></template>
<style>
.wa8wj64_r {
  fill: currentColor;
  d: path("M2 8a6 6 0 0 1 6-6h3c.892 0 1.693.39 2.243 1.007A4 4 0 0 0 13 3H8a5 5 0 0 0-5 5v5q0 .121.007.243A3 3 0 0 1 2 11zm2 .5A4.5 4.5 0 0 1 8.5 4H13c.892 0 1.693.39 2.243 1.007A4 4 0 0 0 15 5H8.5A3.5 3.5 0 0 0 5 8.5V15q0 .121.007.243A3 3 0 0 1 4 13zM9 6a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h6a3 3 0 0 0 3-3V9a3 3 0 0 0-3-3z");
}

</style>
