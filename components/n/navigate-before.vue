<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvzoi796h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:navigate-before" /></template>
<style>
.bvzoi796h {
  fill: currentColor;
  d: path("M14 17.308L8.692 12L14 6.692l.708.708l-4.6 4.6l4.6 4.6z");
}

</style>
