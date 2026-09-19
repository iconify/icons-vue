<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p6bgyybrx"/><path class="r613nccsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tfiletransfer" /></template>
<style>
.p6bgyybrx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.533 5.5l10 10.867H22v11h-8.933v-11H7.533Z");
}

.r613nccsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.867 19.9v11.4h5.6l-9.934 11.2l-10.266-11.2h5.466V19.9Z");
}

</style>
