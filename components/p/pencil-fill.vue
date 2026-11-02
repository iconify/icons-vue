<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7zbyabga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-fill" /></template>
<style>
.u7zbyabga {
  fill: currentColor;
  d: path("M13.414 8L12 6.586l2.293-2.293a2.414 2.414 0 0 1 3.414 0l2 2a2.414 2.414 0 0 1 0 3.414L17.414 12ZM3.293 15.293L10.586 8L16 13.414l-7.293 7.293A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1v-4c0-.265.105-.52.293-.707");
}

</style>
