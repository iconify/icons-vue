<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h51s52bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-off-fill-sharp" /></template>
<style>
.h51s52bgb {
  fill: currentColor;
  d: path("m5.707 1.293l17 17A1 1 0 0 1 22 20v1a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1h1.586l-2-2H7v2h2a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1h2v-3a1 1 0 0 1 1-1h6.586l-2-2H9a1 1 0 0 1-1-1V6.414L4.293 2.707a.999.999 0 1 1 1.414-1.414M15 7.757L9.243 2H15a1 1 0 0 1 1 1v5c0 .206-.064.407-.182.575Z");
}

</style>
