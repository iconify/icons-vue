<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3z2v3bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:nfc-fill-sharp" /></template>
<style>
.o3z2v3bcv {
  fill: currentColor;
  d: path("M3 2h12v11.586L8.707 7.293A1 1 0 0 0 7 8v14H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m14 0h4a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H9V10.414l6.293 6.293A1 1 0 0 0 17 16Z");
}

</style>
