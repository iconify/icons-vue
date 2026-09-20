<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bwy5xt_pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wave-triangle-fill" /></template>
<style>
.bwy5xt_pj {
  fill: currentColor;
  d: path("M216 40H40a16 16 0 0 0-16 16v144a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V56a16 16 0 0 0-16-16m-9.85 93.12l-40 48A8 8 0 0 1 160 184h-.43a8 8 0 0 1-6.23-3.55l-58-87.09l-33.19 39.76a8 8 0 0 1-12.3-10.24l40-48a8 8 0 0 1 12.81.68l58.05 87.09l33.14-39.77a8 8 0 1 1 12.3 10.24");
}

</style>
