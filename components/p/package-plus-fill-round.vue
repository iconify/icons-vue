<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-495ly9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-plus-fill-round" /></template>
<style>
.n-495ly9j {
  fill: currentColor;
  d: path("m3.106 7.553l1-2C4.848 4.069 6.307 3 8 3h8c1.693 0 3.152 1.069 3.894 2.553l1 1.999v.001c.07.139.106.292.106.447v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5V8c0-.155.036-.308.106-.447M5 9v7a3.004 3.004 0 0 0 3 3h8a3 3 0 0 0 3-3V9Zm8 2v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

</style>
