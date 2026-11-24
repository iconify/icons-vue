<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klyouzb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-search-fill-sharp" /></template>
<style>
.klyouzb0c {
  fill: currentColor;
  d: path("M2 20V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m2-1h16V9H4Zm9.708-4.707l1.999 2a.999.999 0 1 1-1.414 1.414l-2-1.999a3 3 0 1 1 1.415-1.415M10 13a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
