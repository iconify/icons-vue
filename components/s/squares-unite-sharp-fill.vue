<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jna1eobao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-unite-sharp-fill" /></template>
<style>
.jna1eobao {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2L15 2C15.5523 2 16 2.4477 16 3L16 8L21 8C21.5523 8 22 8.4477 22 9L22 21C22 21.5523 21.5523 22 21 22L9 22C8.4477 22 8 21.5523 8 21L8 16L3 16C2.4477 16 2 15.5523 2 15L2 3C2 2.4477 2.4477 2 3 2Z");
}

</style>
