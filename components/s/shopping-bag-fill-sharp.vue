<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krp4vgx8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-fill-sharp" /></template>
<style>
.krp4vgx8b {
  fill: currentColor;
  d: path("M8.126 5a4 4 0 0 1 7.748 0H19a1 1 0 0 1 1 1v15a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1Zm2.141 0h3.466a2 2 0 0 0-3.466 0");
}

</style>
