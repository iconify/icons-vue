<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz-3uhbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-size-fill-sharp" /></template>
<style>
.qz-3uhbbv {
  fill: currentColor;
  d: path("M3 4h10a1 1 0 0 1 0 2H9v13a1 1 0 0 1-2 0V6H3a1 1 0 0 1 0-2m12 6h6a1 1 0 0 1 0 2h-2v7a1 1 0 0 1-2 0v-7h-2a1 1 0 0 1 0-2");
}

</style>
