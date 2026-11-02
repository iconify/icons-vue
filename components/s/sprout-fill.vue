<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvl4myhbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sprout-fill" /></template>
<style>
.gvl4myhbs {
  fill: currentColor;
  d: path("M11 13H9a7 7 0 0 1-7-7V4a1 1 0 0 1 1-1h3a7.005 7.005 0 0 1 6.95 6.153A6.97 6.97 0 0 1 18 7h3a1 1 0 0 1 1 1v1a7 7 0 0 1-7 7h-2v4a1 1 0 0 1-2 0Z");
}

</style>
