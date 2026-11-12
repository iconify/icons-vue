<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjnhmoh2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-vibrate-fill" /></template>
<style>
.jjnhmoh2b {
  fill: currentColor;
  d: path("M9 2h6a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3M3.949 5.684l1 3c.068.205.068.427 0 .632L4.054 12l.895 2.684c.068.205.068.427 0 .632l-1 3a1.001 1.001 0 0 1-1.898-.632L2.946 15l-.895-2.684a1 1 0 0 1 0-.632L2.946 9l-.895-2.684a1.001 1.001 0 0 1 1.898-.632m18 12a1.001 1.001 0 0 1-1.898.632l-1-3a1 1 0 0 1 0-.632L19.946 12l-.895-2.684a1 1 0 0 1 0-.632l1-3a1.001 1.001 0 0 1 1.898.632L21.054 9l.895 2.684c.068.205.068.427 0 .632L21.054 15Z");
}

</style>
