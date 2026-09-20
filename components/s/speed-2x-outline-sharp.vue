<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3lva09ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-2x-outline-sharp" /></template>
<style>
.i3lva09ew {
  fill: currentColor;
  d: path("M5 17v-6h4V9H5V7h6v6H7v2h4v2zm7 0l3-5l-3-5h2l2 3.325L18 7h2l-3 5l3 5h-2l-2-3.325L14 17z");
}

</style>
