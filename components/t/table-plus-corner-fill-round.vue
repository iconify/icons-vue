<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fns7kab-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-plus-corner-fill-round" /></template>
<style>
.fns7kab-k {
  fill: currentColor;
  d: path("M11 3v5H3a5 5 0 0 1 5-5Zm10 5h-8V3h3a5 5 0 0 1 5 5M3 10h7v4H3Zm15 3v3h3a1 1 0 0 1 0 2h-3v3a1 1 0 0 1-2 0v-3h-3a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0M3 16h7v4a1 1 0 0 1-1 1H8a5 5 0 0 1-5-5");
}

</style>
