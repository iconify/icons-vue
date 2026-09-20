<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdqs7_96h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-outline-sharp" /></template>
<style>
.pdqs7_96h {
  fill: currentColor;
  d: path("M3 11V3h18v8zm2-2h14V5H5zM3 21v-8h18v8zm2-2h14v-4H5zM5 9V5zm0 10v-4z");
}

</style>
