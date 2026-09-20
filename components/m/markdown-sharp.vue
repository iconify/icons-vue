<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="out532bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:markdown-sharp" /></template>
<style>
.out532bxv {
  fill: currentColor;
  d: path("m16 15l3-3l-1.05-1.075l-1.2 1.2V9h-1.5v3.125l-1.2-1.2L13 12zM2 20V4h20v16zm3.5-5H7v-4.5h1v3h1.5v-3h1V15H12V9H5.5z");
}

</style>
