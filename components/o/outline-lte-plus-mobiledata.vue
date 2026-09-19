<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k94vruz7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-lte-plus-mobiledata" /></template>
<style>
.k94vruz7b {
  fill: currentColor;
  d: path("M3 14h3v2H1V8h2zm2-4h2v6h2v-6h2V8H5zm7 6h5v-2h-3v-1h3v-2h-3v-1h3V8h-5zm12-5h-2V9h-2v2h-2v2h2v2h2v-2h2z");
}

</style>
