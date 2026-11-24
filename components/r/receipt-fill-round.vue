<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fverd9b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-fill-round" /></template>
<style>
.fverd9b1j {
  fill: currentColor;
  d: path("M8 2h8a5 5 0 0 1 5 5v14a1 1 0 0 1-1.447.894L16 20.118l-3.553 1.776a1 1 0 0 1-.894 0L8 20.118l-3.553 1.776A1 1 0 0 1 3 21V7a5 5 0 0 1 5-5m0 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2Z");
}

</style>
