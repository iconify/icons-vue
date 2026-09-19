<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ijyx5lmzk"/><g class="n1mjunbsu"><circle class="r8mg7qbiq"/><circle class="vbmapebvm"/><circle class="sv82cib9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:speech-balloon" /></template>
<style>
.ijyx5lmzk {
  fill: var(--svg-color--4fd1d9, #4fd1d9);
  d: path("M55.4 5H8.6C4.9 5 2 7.9 2 11.5v29.8c0 3.6 2.9 6.5 6.6 6.5h6.9V59l10.4-11.2h29.6c3.6 0 6.6-2.9 6.6-6.5V11.5C62 7.9 59.1 5 55.4 5");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.r8mg7qbiq {
  cx: 16px;
  cy: 26.4px;
  r: 4.2px;
}

.sv82cib9p {
  cx: 48px;
  cy: 26.4px;
  r: 4.2px;
}

.vbmapebvm {
  cx: 32px;
  cy: 26.4px;
  r: 4.2px;
}

</style>
