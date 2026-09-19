<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nypfa9bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-shop-two" /></template>
<style>
.nypfa9bps {
  fill: currentColor;
  d: path("M3 9H1v13h18v-2H3zm15-4V3c0-1.1-.9-2-2-2h-4c-1.1 0-2 .9-2 2v2H5v13h18V5zm-6-2h4v2h-4zm0 12V8l5.5 3z");
}

</style>
