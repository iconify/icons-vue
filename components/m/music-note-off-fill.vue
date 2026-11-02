<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax40g_4se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-off-fill" /></template>
<style>
.ax40g_4se {
  fill: currentColor;
  d: path("m2.707 3.293l18 18a.999.999 0 1 1-1.414 1.414l-6.343-6.343a4.001 4.001 0 1 1-3.314-3.314L1.293 4.707a.999.999 0 1 1 1.414-1.414M11 6c0-1.265 1.076-2.164 2.298-2.167c.399-.001.793.092 1.149.273l4 2a1 1 0 1 1-.894 1.788l-4-2a.6.6 0 0 0-.251-.061c-.093 0-.302.044-.302.167v2a1 1 0 0 1-2 0Z");
}

</style>
