<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwvburbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-lock-corner-fill" /></template>
<style>
.gwvburbnf {
  fill: currentColor;
  d: path("M20 9H10a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1m2 8v3a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2a3 3 0 1 1 6 0a2 2 0 0 1 2 2m-6-2h2a1 1 0 0 0-2 0m-2 2v3h6v-3Z");
}

</style>
