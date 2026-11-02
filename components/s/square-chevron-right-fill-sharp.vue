<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jweiuqbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-right-fill-sharp" /></template>
<style>
.jweiuqbdp {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m10.586-9l-2.293 2.293a.999.999 0 1 0 1.414 1.414l3-3a1 1 0 0 0 0-1.414l-3-3a.999.999 0 1 0-1.414 1.414Z");
}

</style>
