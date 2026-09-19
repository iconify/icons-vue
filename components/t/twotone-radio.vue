<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkecgrbjh"/><path class="n68kiruad"/><circle class="o7zd1cb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-radio" /></template>
<style>
.n68kiruad {
  fill: currentColor;
  d: path("M2 20a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V8c0-1.11-.89-2-2-2H8.3l8.26-3.34L15.88 1L3.24 6.15C2.51 6.43 2 7.17 2 8zM4 8h16v3h-2V9h-2v2H4zm0 5h16v7H4z");
}

.o7zd1cb4l {
  cx: 8px;
  cy: 16.48px;
  r: 2.5px;
  fill: currentColor;
}

.pkecgrbjh {
  fill: currentColor;
  d: path("M20 13H4v7h16zM8 18.98a2.5 2.5 0 0 1 0-5a2.5 2.5 0 0 1 0 5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
