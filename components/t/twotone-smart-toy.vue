<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6m64ekih"/><path class="dfqmxp8ok"/><path class="z1561iuqy"/><circle class="t9q3sbevr"/><circle class="kak3q5brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-smart-toy" /></template>
<style>
.dfqmxp8ok {
  fill: currentColor;
  d: path("M8 15h8v2H8z");
}

.kak3q5brf {
  cx: 9px;
  cy: 11.5px;
  r: 1.5px;
  fill: currentColor;
}

.p6m64ekih {
  fill: currentColor;
  d: path("M18 7H6v12h12zM7.5 11.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5S9.83 13 9 13s-1.5-.67-1.5-1.5M16 17H8v-2h8zm-1-4c-.83 0-1.5-.67-1.5-1.5S14.17 10 15 10s1.5.67 1.5 1.5S15.83 13 15 13");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.t9q3sbevr {
  cx: 15px;
  cy: 11.5px;
  r: 1.5px;
  fill: currentColor;
}

.z1561iuqy {
  fill: currentColor;
  d: path("M20 9V7c0-1.1-.9-2-2-2h-3c0-1.66-1.34-3-3-3S9 3.34 9 5H6c-1.1 0-2 .9-2 2v2c-1.66 0-3 1.34-3 3s1.34 3 3 3v4c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2v-4c1.66 0 3-1.34 3-3s-1.34-3-3-3m-2 10H6V7h12z");
}

</style>
