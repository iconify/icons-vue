<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-w4vvkon"/><circle class="tcdw_t8mf"/><path class="mgzotqbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-style" /></template>
<style>
.i-w4vvkon {
  fill: currentColor;
  d: path("m2.53 19.65l1.34.56v-9.03l-2.43 5.86c-.41 1.02.08 2.19 1.09 2.61m19.5-3.7L17.07 3.98a2.01 2.01 0 0 0-1.81-1.23c-.26 0-.53.04-.79.15L7.1 5.95a2 2 0 0 0-1.08 2.6l4.96 11.97a2 2 0 0 0 2.6 1.08l7.36-3.05a1.994 1.994 0 0 0 1.09-2.6m-9.2 3.8L7.87 7.79l7.35-3.04h.01l4.95 11.95z");
}

.mgzotqbid {
  fill: currentColor;
  d: path("M5.88 19.75c0 1.1.9 2 2 2h1.45l-3.45-8.34z");
}

.tcdw_t8mf {
  cx: 11px;
  cy: 9px;
  r: 1px;
  fill: currentColor;
}

</style>
