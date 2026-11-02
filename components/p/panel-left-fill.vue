<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0vgaj6-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-left-fill" /></template>
<style>
.y0vgaj6-n {
  fill: currentColor;
  d: path("M18 21H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3m-8-2h8a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1h-8Z");
}

</style>
