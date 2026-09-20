<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh9yi6bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:output-outline-sharp" /></template>
<style>
.oh9yi6bap {
  fill: currentColor;
  d: path("M4 20V4h16v3h-1V5H5v14h14v-2h1v3zm12.712-3.712l-.689-.688l3.056-3.1H9.385v-1h9.694l-3.056-3.1l.689-.688L21 12z");
}

</style>
