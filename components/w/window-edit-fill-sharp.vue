<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="corfci-7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-edit-fill-sharp" /></template>
<style>
.corfci-7w {
  fill: currentColor;
  d: path("M2 20V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m2-1h16V9H4Zm4-4c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 11 18H9a1 1 0 0 1-1-1Zm2.586 1l3-3l-.586-.586l-3 3V16Z");
}

</style>
