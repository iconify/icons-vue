<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5rzhzbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-download-fill-sharp" /></template>
<style>
.n5rzhzbbx {
  fill: currentColor;
  d: path("M3 4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm8.293 10.707a1 1 0 0 0 1.414 0l3-3a.999.999 0 1 0-1.414-1.414L13 11.586V7a1 1 0 0 0-2 0v4.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414ZM9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
