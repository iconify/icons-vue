<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v14g3abzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-receiver-fill-sharp" /></template>
<style>
.v14g3abzr {
  fill: currentColor;
  d: path("M16.486 2.143a1 1 0 0 1 1.371.343a1 1 0 0 1-.343 1.371L10.61 8H21a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h3.723ZM6 15a3 3 0 1 0 6 0a3 3 0 0 0-6 0m11-3h-2a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2m-2 4a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2Z");
}

</style>
