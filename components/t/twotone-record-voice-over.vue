<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn_o-eb0d"/><circle class="glxw65bdw"/><path class="emyh9-bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-record-voice-over" /></template>
<style>
.emyh9-bri {
  fill: currentColor;
  d: path("M9 17c-2.69 0-5.77 1.28-6 2h12c-.2-.71-3.3-2-6-2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.glxw65bdw {
  cx: 9px;
  cy: 9px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.hn_o-eb0d {
  fill: currentColor;
  d: path("M9 13c2.21 0 4-1.79 4-4s-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4m0-6c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m0 8c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4m-6 4c.22-.72 3.31-2 6-2c2.7 0 5.8 1.29 6 2zM16.76 5.36l-1.68 1.69c.84 1.18.84 2.71 0 3.89l1.68 1.69c2.02-2.02 2.02-5.07 0-7.27M20.07 2l-1.63 1.63c2.77 3.02 2.77 7.56 0 10.74L20.07 16c3.9-3.89 3.91-9.95 0-14");
}

</style>
