<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_jxfto1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:town-hall-fill" /></template>
<style>
.n_jxfto1i {
  fill: currentColor;
  d: path("M21 22h-6v-3a3 3 0 1 0-6 0v3H3a1 1 0 0 1-1-1v-4a3 3 0 0 1 3-3h1V8a6 6 0 1 1 12 0v6h1a3 3 0 0 1 3 3v4a1 1 0 0 1-1 1M13 7V6a1 1 0 0 0-2 0v2a1 1 0 0 0 1 1h2a1 1 0 0 0 0-2Zm-2 15v-3a1 1 0 0 1 2 0v3Z");
}

</style>
