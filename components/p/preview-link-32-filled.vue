<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ceqylxbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:preview-link-32-filled" /></template>
<style>
.ceqylxbyi {
  fill: currentColor;
  d: path("M25.5 4A4.5 4.5 0 0 1 30 8.5v15a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 23.5v-15A4.5 4.5 0 0 1 6.5 4zM7 22a1 1 0 1 0 0 2h7a1 1 0 1 0 0-2zm11.5-4a1.5 1.5 0 0 0-1.5 1.5v3a1.5 1.5 0 0 0 1.5 1.5h6a1.5 1.5 0 0 0 1.5-1.5v-3a1.5 1.5 0 0 0-1.5-1.5zm5.5 4h-5v-2h5zM7 18a1 1 0 1 0 0 2h7a1 1 0 1 0 0-2zm.5-10A1.5 1.5 0 0 0 6 9.5v5A1.5 1.5 0 0 0 7.5 16h17a1.5 1.5 0 0 0 1.5-1.5v-5A1.5 1.5 0 0 0 24.5 8zM24 14H8v-4h16z");
}

</style>
