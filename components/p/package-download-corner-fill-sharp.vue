<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swz7sl6_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-download-corner-fill-sharp" /></template>
<style>
.swz7sl6_d {
  fill: currentColor;
  d: path("m3.106 7.553l2-4A1 1 0 0 1 6 3h12c.379 0 .725.214.894.553l2 4A1 1 0 0 1 20 9H5v10h3a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1V8c0-.155.036-.308.106-.447m13.187 14.154l-3-3a1 1 0 0 1 1.414-1.414L16 18.586V13a1 1 0 0 1 2 0v5.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0");
}

</style>
