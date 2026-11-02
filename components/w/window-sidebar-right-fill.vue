<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dblba_boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sidebar-right-fill" /></template>
<style>
.dblba_boc {
  fill: currentColor;
  d: path("M5 21a3.004 3.004 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3Zm-1-3a1 1 0 0 0 1 1h9V9H4Z");
}

</style>
