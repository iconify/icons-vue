<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdn7b7brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-4-bulk" /></template>
<style>
.bdn7b7brg {
  fill: currentColor;
  d: path("M14 17H7a1 1 0 0 1-.832-1.555l8-12A1 1 0 0 1 16 4v11h1a1 1 0 0 1 0 2h-1v3a1 1 0 0 1-2 0Zm0-2V7.303L8.869 15Z");
}

</style>
