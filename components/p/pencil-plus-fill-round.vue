<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swvidx8br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-plus-fill-round" /></template>
<style>
.swvidx8br {
  fill: currentColor;
  d: path("M8 6h2a1 1 0 0 1 0 2H8v2a1 1 0 0 1-2 0V8H4a1 1 0 0 1 0-2h2V4a1 1 0 0 1 2 0Zm7.414 3L14 7.586l.293-.293a2.414 2.414 0 0 1 3.414 0l1 1a2.414 2.414 0 0 1 0 3.414l-.293.293ZM5 20v-3c0-.265.105-.52.293-.707L12.586 9L17 13.414l-7.293 7.293A1 1 0 0 1 9 21H6a1 1 0 0 1-1-1");
}

</style>
