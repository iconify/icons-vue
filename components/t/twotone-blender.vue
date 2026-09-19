<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5tk8vbcb"/><path class="hokg2nbqm"/><circle class="oa7jysr2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-blender" /></template>
<style>
.hokg2nbqm {
  fill: currentColor;
  d: path("M16.13 15.13L18 3h-4V2h-4v1H5c-1.1 0-2 .9-2 2v4c0 1.1.9 2 2 2h2.23l.64 4.13C6.74 16.05 6 17.43 6 19v1c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2v-1c0-1.57-.74-2.95-1.87-3.87M5 9V5h1.31l.62 4zm10.67-4l-1.38 9H9.72L8.33 5zM16 20H8v-1c0-1.65 1.35-3 3-3h2c1.65 0 3 1.35 3 3z");
}

.oa7jysr2p {
  cx: 12px;
  cy: 18px;
  r: 1px;
  fill: currentColor;
}

.x5tk8vbcb {
  fill: currentColor;
  d: path("M13 16h-2c-1.65 0-3 1.35-3 3v1h8v-1c0-1.65-1.35-3-3-3m-1 3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
