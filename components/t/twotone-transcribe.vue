<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="glxw65bdw"/><path class="h44l2rbqu"/><path class="v3s2h9k2f"/><path class="w8vco-mbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-transcribe" /></template>
<style>
.glxw65bdw {
  cx: 9px;
  cy: 9px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.h44l2rbqu {
  fill: currentColor;
  d: path("M14.48 17.34C13.29 16.73 11.37 16 9 16s-4.29.73-5.48 1.34c-.32.16-.52.5-.52.88V19h12v-.78c0-.38-.2-.72-.52-.88");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.v3s2h9k2f {
  fill: currentColor;
  d: path("M17.93 2c-3.9 3.89-3.91 9.95 0 14l1.63-1.63c-2.77-3.02-2.77-7.56 0-10.74zM9 13c2.21 0 4-1.79 4-4s-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4m0-6c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m6.39 8.56C13.71 14.7 11.53 14 9 14s-4.71.7-6.39 1.56A2.97 2.97 0 0 0 1 18.22V21h16v-2.78c0-1.12-.61-2.15-1.61-2.66M15 19H3v-.78c0-.38.2-.72.52-.88C4.71 16.73 6.63 16 9 16s4.29.73 5.48 1.34c.32.16.52.5.52.88z");
}

.w8vco-mbi {
  fill: currentColor;
  d: path("m22.92 7.06l-1.68-1.69c-2.02 2.02-2.02 5.07 0 7.27l1.68-1.69a3.32 3.32 0 0 1 0-3.89");
}

</style>
