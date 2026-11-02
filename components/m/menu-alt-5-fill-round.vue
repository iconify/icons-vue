<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rha5-6c-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-alt-5-fill-round" /></template>
<style>
.rha5-6c-d {
  fill: currentColor;
  d: path("M19 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm-6 5a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z");
}

</style>
