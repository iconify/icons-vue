<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w42mnbcwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-size-increase-fill" /></template>
<style>
.w42mnbcwf {
  fill: currentColor;
  d: path("M3 4h10a1 1 0 0 1 0 2H9v13a1 1 0 0 1-2 0V6H3a1 1 0 0 1 0-2m16 5v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2V9a1 1 0 0 1 2 0");
}

</style>
