<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3n435b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-barcode" /></template>
<style>
.e3n435b9b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 6h1v12H2zm2 0h2v12H4zm4 0h1v12H8zm2 0h3v12h-3zm4 0h1v12h-1zm3 0h1v12h-1zm2 0h1v12h-1zm2 0h1v12h-1z");
}

</style>
