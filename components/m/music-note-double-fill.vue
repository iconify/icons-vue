<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmt-nlllv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-double-fill" /></template>
<style>
.kmt-nlllv {
  fill: currentColor;
  d: path("M11 6c0-1.265 1.076-2.164 2.298-2.167c.399-.001.793.092 1.149.273l4 2a1 1 0 1 1-.894 1.788l-4-2a.6.6 0 0 0-.251-.061c-.093 0-.302.044-.302.167v2.382l3.447 1.724a1 1 0 1 1-.894 1.788L13 10.618V17a4.001 4.001 0 1 1-2-3.465Z");
}

</style>
