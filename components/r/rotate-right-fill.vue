<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1547j00t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-right-fill" /></template>
<style>
.g1547j00t {
  fill: currentColor;
  d: path("m9.707 2.293l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L9.586 7H7a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0V8a3 3 0 0 1 3-3h2.586L8.293 3.707a.999.999 0 1 1 1.414-1.414M6 14v4a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2h1a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-4a1 1 0 0 1 2 0");
}

</style>
