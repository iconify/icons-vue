<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl-36tbun"/><circle class="x0re21bee"/><path class="a4fw41x8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-devices-other" /></template>
<style>
.a4fw41x8b {
  fill: currentColor;
  d: path("M3 6h18V4H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h4v-2H3zm19 2h-6c-.5 0-1 .5-1 1v10c0 .5.5 1 1 1h6c.5 0 1-.5 1-1V9c0-.5-.5-1-1-1m-1 10h-4v-8h4zm-8-6H9v1.78c-.61.55-1 1.33-1 2.22s.39 1.67 1 2.22V20h4v-1.78c.61-.55 1-1.34 1-2.22s-.39-1.67-1-2.22zm-2 5.5c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
}

.x0re21bee {
  cx: 11px;
  cy: 16px;
  r: 1.5px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xl-36tbun {
  fill: currentColor;
  d: path("M17 10h4v8h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
