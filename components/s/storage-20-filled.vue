<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v-q_x-b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:storage-20-filled" /></template>
<style>
.v-q_x-b7i {
  fill: currentColor;
  d: path("M2 8.5A2.5 2.5 0 0 1 4.5 6h11A2.5 2.5 0 0 1 18 8.5v3a2.5 2.5 0 0 1-2.5 2.5h-11A2.5 2.5 0 0 1 2 11.5zM13 9a1 1 0 1 0-2 0a1 1 0 0 0 2 0m3 0a1 1 0 1 0-2 0a1 1 0 0 0 2 0");
}

</style>
