<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aq-1w6b7c"/><path class="mjy37qbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wyze" /></template>
<style>
.aq-1w6b7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-3.456 22.956H39.5m-4.456-8.912H39.5M35.044 24h2.905m-2.905-4.456v8.912");
}

.mjy37qbaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.413 19.544l-2.229 8.912l-2.228-8.912l-2.228 8.912L8.5 19.544m16.763 0L22.31 24l-2.952-4.456m2.952 8.912V24m4.893-4.456h5.904l-5.904 8.912h5.904");
}

</style>
