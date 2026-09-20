<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kji1qobrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-snippet-outline-sharp" /></template>
<style>
.kji1qobrj {
  fill: currentColor;
  d: path("M5 19h14V9.614L14.387 5H5zm-1 1V4h10.789L20 9.211V20zm3.5-4h9v-1h-9zm0-3.5h9v-1h-9zm0-3.5h5.73V8H7.5zM5 19V5z");
}

</style>
