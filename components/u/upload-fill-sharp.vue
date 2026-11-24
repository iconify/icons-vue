<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5gn817mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:upload-fill-sharp" /></template>
<style>
.t5gn817mw {
  fill: currentColor;
  d: path("M15.293 8.707L13 6.414V16a1 1 0 0 1-2 0V6.414L8.707 8.707a.999.999 0 1 1-1.414-1.414l4-4a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414M5 16v3h14v-3a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0");
}

</style>
