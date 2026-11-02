<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqosa3bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swatches-fill" /></template>
<style>
.wqosa3bua {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v1.586l1.293-1.293a2.414 2.414 0 0 1 3.414 0l3 3a2.414 2.414 0 0 1 0 3.414L18.414 13H19a3 3 0 0 1 3 3v3a3 3 0 0 1-3 3H7a5 5 0 0 1-5-5Zm13.293 8.293l3-3a.414.414 0 0 0 0-.586l-3-3a.414.414 0 0 0-.586 0L12 9.414v7.172ZM19 20a1 1 0 0 0 1-1v-3a1 1 0 0 0-1-1h-2.586l-5 5ZM7 16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
