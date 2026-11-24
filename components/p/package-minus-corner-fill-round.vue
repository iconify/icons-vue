<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p034uhbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-minus-corner-fill-round" /></template>
<style>
.p034uhbin {
  fill: currentColor;
  d: path("m3.106 7.553l1-2C4.848 4.069 6.307 3 8 3h8c1.693 0 3.152 1.069 3.894 2.553l1 2A1 1 0 0 1 20 9H5v7a3 3 0 0 0 3 3a1 1 0 0 1 0 2a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 16V8c0-.155.036-.308.106-.447M13 15h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
