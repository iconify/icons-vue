<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cezjoccyj"/><path class="j056tnk8e"/><path class="wv4odjb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simexplorer" /></template>
<style>
.cezjoccyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.87 28.74h-4.73v2.68h-4.69v2.68h-9.38v-5.36h4.69v-2.68h4.69v-2.68h9.42ZM41.68 13H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9A2.18 2.18 0 0 0 4.5 11v7.29h39v-3.42A1.83 1.83 0 0 0 41.68 13");
}

.j056tnk8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.28h-39V37a2.18 2.18 0 0 0 2.17 2.2h34.65A2.18 2.18 0 0 0 43.5 37Z");
}

.wv4odjb5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.45 26.06v2.68h4.69m-9.38 0v2.68h4.71");
}

</style>
