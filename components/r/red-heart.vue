<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x_a1g2-sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:red-heart" /></template>
<style>
.x_a1g2-sl {
  fill: currentColor;
  d: path("M61.072 17.583C54.678-.04 33.918 7.867 31.998 16.668c-2.641-9.379-22.89-16.376-29.07.928c-6.881 19.273 26.67 36.57 29.07 39.404c2.398-2.252 35.953-20.457 29.074-39.417");
}

</style>
