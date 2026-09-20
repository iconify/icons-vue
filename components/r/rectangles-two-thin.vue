<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lcsnw3b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rectangles-two-thin" /></template>
<style>
.lcsnw3b_n {
  fill: currentColor;
  d: path("M208 140H48a12 12 0 0 0-12 12v40a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12v-40a12 12 0 0 0-12-12m4 52a4 4 0 0 1-4 4H48a4 4 0 0 1-4-4v-40a4 4 0 0 1 4-4h160a4 4 0 0 1 4 4Zm-4-140H48a12 12 0 0 0-12 12v40a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12V64a12 12 0 0 0-12-12m4 52a4 4 0 0 1-4 4H48a4 4 0 0 1-4-4V64a4 4 0 0 1 4-4h160a4 4 0 0 1 4 4Z");
}

</style>
