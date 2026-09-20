<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld22hhb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:note-add-outline" /></template>
<style>
.ld22hhb6u {
  fill: currentColor;
  d: path("M11 18h2v-3h3v-2h-3v-3h-2v3H8v2h3zm-5 4q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v12q0 .825-.587 1.413T18 22zm7-13V4H6v16h12V9zM6 4v5zv16z");
}

</style>
