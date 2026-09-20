<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tmqt3bckx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mic-off-12-regular" /></template>
<style>
.tmqt3bckx {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .708 0l9 9a.5.5 0 0 1-.708.708L8.16 8.867a4 4 0 0 1-1.66.602V10.5a.5.5 0 1 1-1 0V9.47A4 4 0 0 1 2 5.5a.5.5 0 1 1 1 0a3 3 0 0 0 4.43 2.638l-.754-.755A2 2 0 0 1 4 5.5v-.793L1.146 1.854a.5.5 0 0 1 0-.708M7 3v1.879l.97.97Q8 5.679 8 5.5V3a2 2 0 0 0-3.784-.905l.79.79A1 1 0 0 1 7 3m1.772 3.65l.749.75A4 4 0 0 0 10 5.5a.5.5 0 1 0-1 0c0 .408-.081.796-.228 1.15");
}

</style>
