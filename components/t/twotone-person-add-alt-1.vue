<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="q1j8406-g"/><path class="zebpi-dtd"/><path class="fxe5hqbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-person-add-alt-1" /></template>
<style>
.fxe5hqbli {
  fill: currentColor;
  d: path("M9 14c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4m-6 4c.2-.71 3.3-2 6-2c2.69 0 5.78 1.28 6 2zm17-8V7h-2v3h-3v2h3v3h2v-3h3v-2zM9 12c2.21 0 4-1.79 4-4s-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4m0-6c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2");
}

.q1j8406-g {
  cx: 9px;
  cy: 8px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zebpi-dtd {
  fill: currentColor;
  d: path("M9 16c-2.7 0-5.8 1.29-6 2h12c-.22-.72-3.31-2-6-2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
