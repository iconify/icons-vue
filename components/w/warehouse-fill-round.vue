<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8e80obax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-fill-round" /></template>
<style>
.b8e80obax {
  fill: currentColor;
  d: path("M21 22h-5v-9a1 1 0 0 0-1-1H9a1 1 0 0 0-1 1v9H3a1 1 0 0 1 0-2h1v-8c0-1.693 1.069-3.152 2.553-3.894l4-2A1 1 0 0 1 11 6h2c.155 0 .308.036.447.106l4 2C18.931 8.848 20 10.307 20 12v8h1a1 1 0 0 1 0 2m-8-6h-2a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2m0 4h-2a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2");
}

</style>
