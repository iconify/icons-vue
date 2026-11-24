<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4px_bbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-fill" /></template>
<style>
.b4px_bbxo {
  fill: currentColor;
  d: path("M6 2h12a3 3 0 0 1 3 3v16a1 1 0 0 1-1.447.894L16 20.118l-3.553 1.776a1 1 0 0 1-.894 0L8 20.118l-3.553 1.776A1 1 0 0 1 3 21V5a3 3 0 0 1 3-3m2 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2Z");
}

</style>
