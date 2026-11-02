<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2xtnil3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-double-large-fill-sharp" /></template>
<style>
.l2xtnil3l {
  fill: currentColor;
  d: path("M21 8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
