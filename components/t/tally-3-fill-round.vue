<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ypinyvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tally-3-fill-round" /></template>
<style>
.p1ypinyvq {
  fill: currentColor;
  d: path("M9 19a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>
