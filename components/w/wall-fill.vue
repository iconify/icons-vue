<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x0_1ujbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wall-fill" /></template>
<style>
.x0_1ujbia {
  fill: currentColor;
  d: path("M232 56v32a4 4 0 0 1-4 4h-92V52a4 4 0 0 1 4-4h84a8 8 0 0 1 8 8m-4 52h-44v44h44a4 4 0 0 0 4-4v-36a4 4 0 0 0-4-4M88 152h80v-44H88Zm-60 0h44v-44H28a4 4 0 0 0-4 4v36a4 4 0 0 0 4 4m200 16h-92v36a4 4 0 0 0 4 4h84a8 8 0 0 0 8-8v-28a4 4 0 0 0-4-4M28 92h92V52a4 4 0 0 0-4-4H32a8 8 0 0 0-8 8v32a4 4 0 0 0 4 4m-4 80v28a8 8 0 0 0 8 8h84a4 4 0 0 0 4-4v-36H28a4 4 0 0 0-4 4");
}

</style>
