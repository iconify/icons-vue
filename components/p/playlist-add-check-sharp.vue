<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnwpx0-vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:playlist-add-check-sharp" /></template>
<style>
.nnwpx0-vt {
  fill: currentColor;
  d: path("M3 16v-2h8v2zm0-4v-2h12v2zm0-4V6h12v2zm13.35 11l-3.55-3.55l1.4-1.4l2.15 2.1l4.25-4.25l1.4 1.45z");
}

</style>
