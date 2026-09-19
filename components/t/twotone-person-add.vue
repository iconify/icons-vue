<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrpjtrbai"/><circle class="er_9nmfrk"/><path class="qm5zybwfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-person-add" /></template>
<style>
.er_9nmfrk {
  cx: 15px;
  cy: 8px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qm5zybwfc {
  fill: currentColor;
  d: path("M15 12c2.21 0 4-1.79 4-4s-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4m0-6c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m0 8c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4m-6 4c.22-.72 3.31-2 6-2c2.7 0 5.8 1.29 6 2zm-3-3v-3h3v-2H6V7H4v3H1v2h3v3z");
}

.xrpjtrbai {
  fill: currentColor;
  d: path("M15 16c-2.69 0-5.77 1.28-6 2h12c-.2-.71-3.3-2-6-2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
