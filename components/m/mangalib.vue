<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="liawmobsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mangalib" /></template>
<style>
.liawmobsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 18.5v-9a4 4 0 0 1 4-4h9m24 24v9a4 4 0 0 1-4 4h-9m-16-8.023V13.5l10.5 21l10.5-20.968V34.5");
}

</style>
