<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv2hdmksd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:move-selection-down-outline" /></template>
<style>
.zv2hdmksd {
  fill: currentColor;
  d: path("M6 22V10h12v12zm2-2h8v-8H8zM6 8V6h2v2zm10 0V6h2v2zM6 4V2h2v2zm5 0V2h2v2zm5 0V2h2v2zm-4 12");
}

</style>
