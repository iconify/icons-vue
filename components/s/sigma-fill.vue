<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q9dpeac2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sigma-fill" /></template>
<style>
.q9dpeac2k {
  fill: currentColor;
  d: path("M200 24H56a16 16 0 0 0-16 16v176a16 16 0 0 0 16 16h144a16 16 0 0 0 16-16V40a16 16 0 0 0-16-16m-16 64a8 8 0 0 1-16 0V72H96l38.4 51.2a8 8 0 0 1 0 9.6L96 184h72v-16a8 8 0 0 1 16 0v24a8 8 0 0 1-8 8H80a8 8 0 0 1-6.4-12.8L118 128L73.6 68.8A8 8 0 0 1 80 56h96a8 8 0 0 1 8 8Z");
}

</style>
