<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="scox17bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-left-20-filled" /></template>
<style>
.scox17bag {
  fill: currentColor;
  d: path("M2.786 8.68a1.5 1.5 0 0 0 0 2.638l11.998 6.5A1.5 1.5 0 0 0 17 16.498V3.5a1.5 1.5 0 0 0-2.215-1.32z");
}

</style>
