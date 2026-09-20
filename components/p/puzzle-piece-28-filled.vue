<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ax3uyjb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:puzzle-piece-28-filled" /></template>
<style>
.ax3uyjb-c {
  fill: currentColor;
  d: path("M15 2a3 3 0 0 0-3 3v1H9.25A2.25 2.25 0 0 0 7 8.25V11H6a3 3 0 1 0 0 6h1v2.75A2.25 2.25 0 0 0 9.25 22H12v1a3 3 0 1 0 6 0v-1h2.75A2.25 2.25 0 0 0 23 19.75V16h-2a2 2 0 1 1 0-4h2V8.25A2.25 2.25 0 0 0 20.75 6H18V5a3 3 0 0 0-3-3");
}

</style>
