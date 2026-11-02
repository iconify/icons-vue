<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evixo2yul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reply-all-bulk-round" /></template>
<style>
.evixo2yul {
  fill: currentColor;
  d: path("M5.414 8h3.172l3.707-3.707a.999.999 0 1 1 1.414 1.414L11.414 8H17a5 5 0 0 1 5 5v2a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20h-6a1 1 0 0 1 0-2h6a3 3 0 0 0 3-3v-2a3 3 0 0 0-3-3h-5.586l2.293 2.293a.999.999 0 1 1-1.414 1.414L8.586 10H5.414l2.293 2.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414Z");
}

</style>
