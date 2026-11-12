<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqznzlipx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:security-key-fill-round" /></template>
<style>
.sqznzlipx {
  fill: currentColor;
  d: path("M2 11a5 5 0 0 1 5-5h4a4.99 4.99 0 0 1 4.001 2H20a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-4.999A4.99 4.99 0 0 1 11 18H7a5 5 0 0 1-5-5Zm8 2v-2a1 1 0 0 0-2 0v2a1 1 0 0 0 2 0m6-2v2c0 .335-.032.672-.099 1H20v-1h-1a1 1 0 0 1 0-2h1v-1h-4.099c.067.328.099.665.099 1");
}

</style>
