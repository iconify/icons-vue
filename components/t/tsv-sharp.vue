<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky_32tf5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tsv-sharp" /></template>
<style>
.ky_32tf5t {
  fill: currentColor;
  d: path("M2 20V4h20v16zm4.25-5h1.5v-4.5H9V9H5v1.5h1.25zm3.25 0h4v-3.65H11v-.85h2.5V9h-4v3.6H12v.9H9.5zm6.25 0h1.5L19 9h-1.5l-1 3.45l-1-3.45H14z");
}

</style>
