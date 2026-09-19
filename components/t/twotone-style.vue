<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1o-97ksr"/><path class="x5wyg3bio"/><circle class="tcdw_t8mf"/><path class="s9c8qxb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-style" /></template>
<style>
.s9c8qxb8y {
  fill: currentColor;
  d: path("m9.33 21.75l-3.45-8.34v6.34c0 1.1.9 2 2 2z");
}

.tcdw_t8mf {
  cx: 11px;
  cy: 9px;
  r: 1px;
  fill: currentColor;
}

.x1o-97ksr {
  fill: currentColor;
  d: path("M15.22 4.75L7.87 7.79l4.96 11.96l7.35-3.05zM11 10c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.x5wyg3bio {
  fill: currentColor;
  d: path("m3.87 11.18l-2.43 5.86c-.41 1.02.08 2.19 1.09 2.61l1.34.56zm18.16 4.77L17.07 3.98a2.01 2.01 0 0 0-1.81-1.23c-.26 0-.53.04-.79.15L7.1 5.95a2 2 0 0 0-1.08 2.6l4.96 11.97a2 2 0 0 0 2.6 1.08l7.36-3.05a1.994 1.994 0 0 0 1.09-2.6m-9.2 3.8L7.87 7.79l7.35-3.04h.01l4.95 11.95z");
}

</style>
