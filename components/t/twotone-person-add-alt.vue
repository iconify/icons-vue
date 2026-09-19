<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="q1j8406-g"/><path class="rsa3mhb0h"/><path class="bb39iksht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-person-add-alt" /></template>
<style>
.bb39iksht {
  fill: currentColor;
  d: path("M9 12c2.21 0 4-1.79 4-4s-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4m0-6c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m11 3V6h-2v3h-3v2h3v3h2v-3h3V9zm-4.61 5.56C13.71 13.7 11.53 13 9 13s-4.71.7-6.39 1.56A2.97 2.97 0 0 0 1 17.22V20h16v-2.78c0-1.12-.61-2.15-1.61-2.66M15 18H3v-.78c0-.38.2-.72.52-.88C4.71 15.73 6.63 15 9 15s4.29.73 5.48 1.34c.32.16.52.5.52.88z");
}

.q1j8406-g {
  cx: 9px;
  cy: 8px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rsa3mhb0h {
  fill: currentColor;
  d: path("M14.48 16.34C13.29 15.73 11.37 15 9 15s-4.29.73-5.48 1.34c-.32.16-.52.5-.52.88V18h12v-.78c0-.38-.2-.72-.52-.88");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
