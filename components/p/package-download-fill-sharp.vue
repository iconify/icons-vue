<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgral9b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-download-fill-sharp" /></template>
<style>
.xgral9b9d {
  fill: currentColor;
  d: path("m3.106 7.553l2-4A1 1 0 0 1 6 3h12c.379 0 .725.214.894.553l2 4c.07.139.106.292.106.447v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V8c0-.155.036-.308.106-.447M5 9v10h14V9Zm3.293 5.707a.999.999 0 1 1 1.414-1.414L11 14.586V11a1 1 0 0 1 2 0v3.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0Z");
}

</style>
