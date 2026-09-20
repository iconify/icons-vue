<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vgfpgtbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:share-thin" /></template>
<style>
.vgfpgtbif {
  fill: currentColor;
  d: path("m226.83 106.83l-48 48a4 4 0 0 1-5.66-5.66L214.34 108H165a92 92 0 0 0-89.11 69a4 4 0 0 1-3.89 3a4 4 0 0 1-1-.13a4 4 0 0 1-2.87-4.87A99.93 99.93 0 0 1 165 100h49.36l-41.19-41.17a4 4 0 0 1 5.66-5.66l48 48a4 4 0 0 1 0 5.66M192 212H36V88a4 4 0 0 0-8 0v128a4 4 0 0 0 4 4h160a4 4 0 0 0 0-8");
}

</style>
