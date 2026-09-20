<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cxtx1hzag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:receipt-light" /></template>
<style>
.cxtx1hzag {
  fill: currentColor;
  d: path("M182 104a6 6 0 0 1-6 6H80a6 6 0 0 1 0-12h96a6 6 0 0 1 6 6m-6 26H80a6 6 0 0 0 0 12h96a6 6 0 0 0 0-12m54-74v152a6 6 0 0 1-2.85 5.1a5.93 5.93 0 0 1-3.15.9a6 6 0 0 1-2.68-.63L192 198.71l-29.32 14.66a6 6 0 0 1-5.36 0L128 198.71l-29.32 14.66a6 6 0 0 1-5.36 0L64 198.71l-29.32 14.66A6 6 0 0 1 26 208V56a14 14 0 0 1 14-14h176a14 14 0 0 1 14 14m-12 0a2 2 0 0 0-2-2H40a2 2 0 0 0-2 2v142.29l23.32-11.66a6 6 0 0 1 5.36 0L96 201.29l29.32-14.66a6 6 0 0 1 5.36 0L160 201.29l29.32-14.66a6 6 0 0 1 5.36 0L218 198.29Z");
}

</style>
