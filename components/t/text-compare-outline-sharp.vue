<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v66md2bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-compare-outline-sharp" /></template>
<style>
.v66md2bzz {
  fill: currentColor;
  d: path("M10 23v-2H3V3h7V1h2v22zm-5-4h5v-2H7v-2h3v-2H7v-2h3V9H7V7h3V5H5zm9-14V3h7v18h-7v-2h5V5zm0 8v-2h3v2zm0-4V7h3v2zm-4 3");
}

</style>
