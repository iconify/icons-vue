<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnl2zib4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-center-sharp" /></template>
<style>
.mnl2zib4p {
  fill: currentColor;
  d: path("M3 19V5h18v14zm5.154-4.154h7.692V9.154H8.154z");
}

</style>
