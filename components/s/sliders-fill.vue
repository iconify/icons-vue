<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nsz55lbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sliders-fill" /></template>
<style>
.nsz55lbvw {
  fill: currentColor;
  d: path("M84 136a28 28 0 0 1-20 26.83V216a8 8 0 0 1-16 0v-53.17a28 28 0 0 1 0-53.66V40a8 8 0 0 1 16 0v69.17A28 28 0 0 1 84 136m52-74.83V40a8 8 0 0 0-16 0v21.17a28 28 0 0 0 0 53.66V216a8 8 0 0 0 16 0V114.83a28 28 0 0 0 0-53.66m72 80V40a8 8 0 0 0-16 0v101.17a28 28 0 0 0 0 53.66V216a8 8 0 0 0 16 0v-21.17a28 28 0 0 0 0-53.66");
}

</style>
