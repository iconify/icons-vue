<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="u40lczbbd"/><circle class="jmkjaobdd"/><circle class="n-1wyuzcv"/><path class="kzcbzlbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-workspaces" /></template>
<style>
.jmkjaobdd {
  cx: 12px;
  cy: 7px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.kzcbzlbge {
  fill: currentColor;
  d: path("M18 13c-2.2 0-4 1.8-4 4s1.8 4 4 4s4-1.8 4-4s-1.8-4-4-4m0 6c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2M6 13c-2.2 0-4 1.8-4 4s1.8 4 4 4s4-1.8 4-4s-1.8-4-4-4m0 6c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2M16 7c0-2.2-1.8-4-4-4S8 4.8 8 7s1.8 4 4 4s4-1.8 4-4m-4 2c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2");
}

.n-1wyuzcv {
  cx: 18px;
  cy: 17px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.u40lczbbd {
  cx: 6px;
  cy: 17px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
