<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v5-h7acfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tag-simple-light" /></template>
<style>
.v5-h7acfj {
  fill: currentColor;
  d: path("m245 124.67l-45.63-68.44A14 14 0 0 0 187.72 50H40a14 14 0 0 0-14 14v128a14 14 0 0 0 14 14h147.72a14 14 0 0 0 11.65-6.23L245 131.33a6 6 0 0 0 0-6.66m-55.61 68.44a2 2 0 0 1-1.66.89H40a2 2 0 0 1-2-2V64a2 2 0 0 1 2-2h147.72a2 2 0 0 1 1.66.89L232.79 128Z");
}

</style>
