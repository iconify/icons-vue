<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ro0i1owxi"/><circle class="vaumy7pmm"/><path class="dfw4y1g3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-nature-people" /></template>
<style>
.dfw4y1g3q {
  fill: currentColor;
  d: path("M15.17 2.17c-3.87 0-7 3.13-7 7A6.98 6.98 0 0 0 14 16.06V20H6v-3h1v-4c0-.55-.45-1-1-1H3c-.55 0-1 .45-1 1v4h1v5h16v-2h-3v-3.88a7 7 0 0 0 6.17-6.95c0-3.87-3.13-7-7-7m0 12c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5");
}

.ro0i1owxi {
  cx: 15.17px;
  cy: 9.17px;
  r: 5px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.vaumy7pmm {
  cx: 4.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
