<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ante_u81j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tetris-app-24-filled" /></template>
<style>
.ante_u81j {
  fill: currentColor;
  d: path("M8 3a1 1 0 0 1 1-1h4v5H8zM3 8a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h4V8zm10 0H8v5h4a1 1 0 0 0 1-1zm5-6h-4v5h4a1 1 0 0 0 1-1V3a1 1 0 0 0-1-1M4 17a1 1 0 0 1 1-1h4v5H5a1 1 0 0 1-1-1zm11-1h-5v5h5zm1 0h5v4a1 1 0 0 1-1 1h-4zm1-6a1 1 0 0 0-1 1v4h5v-4a1 1 0 0 0-1-1z");
}

</style>
