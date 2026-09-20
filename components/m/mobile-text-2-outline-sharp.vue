<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p939r-vwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-text-2-outline-sharp" /></template>
<style>
.p939r-vwy {
  fill: currentColor;
  d: path("M8.385 11.596h7.307v-1H8.385zm1 2.885h5.307v-1H9.385zM6 22V2h12.077v4.83H19v3.686h-.923V22zm1-1h10.077V3H7zm0 0V3z");
}

</style>
