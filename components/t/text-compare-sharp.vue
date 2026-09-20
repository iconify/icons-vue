<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnnlxs4un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-compare-sharp" /></template>
<style>
.dnnlxs4un {
  fill: currentColor;
  d: path("M10 23v-2H3V3h7V1h2v22zm4-18V3h7v18h-7v-2h5V5zm0 8v-2h3v2zm0-4V7h3v2zm-7 8h3v-2H7zm0-4h3v-2H7zm0-4h3V7H7z");
}

</style>
