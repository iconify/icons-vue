<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le5ojcc3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-fill-round" /></template>
<style>
.le5ojcc3w {
  fill: currentColor;
  d: path("M10 3c1.317 0 2.748.335 3.707 1.293l4 4a5.243 5.243 0 0 1 0 7.414l-2 2a5.243 5.243 0 0 1-7.414 0l-4-4C3.335 12.748 3 11.317 3 10V8a5 5 0 0 1 5-5ZM7.158 8.221a2 2 0 1 0 3.684 1.558A2 2 0 0 0 7.158 8.22");
}

</style>
