<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulizmbqhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-close-fill-sharp" /></template>
<style>
.ulizmbqhc {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1M9.707 8.293a.999.999 0 1 0-1.414 1.414L10.586 12l-2.293 2.293a.999.999 0 1 0 1.414 1.414L12 13.414l2.293 2.293a.999.999 0 1 0 1.414-1.414L13.414 12l2.293-2.293a.999.999 0 1 0-1.414-1.414L12 10.586Z");
}

</style>
