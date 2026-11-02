<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u17he8btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:row-plus-fill-round" /></template>
<style>
.u17he8btl {
  fill: currentColor;
  d: path("M7 3h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8m6 13h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0Z");
}

</style>
