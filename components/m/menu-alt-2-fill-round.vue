<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5jngf2xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-alt-2-fill-round" /></template>
<style>
.f5jngf2xf {
  fill: currentColor;
  d: path("M19 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

</style>
