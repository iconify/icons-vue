<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6ehoac1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shelves" /></template>
<style>
.k6ehoac1q {
  fill: currentColor;
  d: path("M3 23V1h2v2h14V1h2v22h-2v-2H5v2zm2-12h2V7h6v4h6V5H5zm0 8h6v-4h6v4h2v-6H5z");
}

</style>
