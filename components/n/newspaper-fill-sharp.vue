<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnk78sbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:newspaper-fill-sharp" /></template>
<style>
.rnk78sbet {
  fill: currentColor;
  d: path("M8 3h13a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H8ZM6 7v14H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1Zm12 0h-6a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2m-6 4a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Zm6 4h-6a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
