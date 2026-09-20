<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="bvrvdmb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tiktok-plugin" /></template>
<style>
.bvrvdmb7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 27.664v-7.328h2.399c1.356 0 2.456 1.102 2.456 2.461s-1.1 2.461-2.456 2.461H8.5m6.564-4.922v7.328h3.664m1.081-7.328v4.9a2.427 2.427 0 1 0 4.855 0v-4.9m6.563 2.427a2.427 2.427 0 1 0-4.855 0v2.474a2.427 2.427 0 1 0 4.855 0H28.8m4.136-4.901v7.328m1.709 0v-7.328l4.855 7.328v-7.328");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
