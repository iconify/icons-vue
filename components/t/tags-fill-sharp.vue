<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wugsonbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tags-fill-sharp" /></template>
<style>
.wugsonbuz {
  fill: currentColor;
  d: path("M9 5c.265 0 .52.105.707.293l6 6a1 1 0 0 1 0 1.414l-6 6a1 1 0 0 1-1.414 0l-6-6A1 1 0 0 1 2 12V6a1 1 0 0 1 1-1Zm6.707.293l6 6a1 1 0 0 1 0 1.414l-6 6a.999.999 0 1 1-1.414-1.414L19.586 12l-5.293-5.293a.999.999 0 1 1 1.414-1.414M7 9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
