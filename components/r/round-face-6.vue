<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z37qpq2co"/><circle class="t8-_arz4f"/><circle class="pt3nek-ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-face-6" /></template>
<style>
.pt3nek-ut {
  cx: 15px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

.t8-_arz4f {
  cx: 9px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

.z37qpq2co {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.41 0-8-3.59-8-8v-.03c2.31-.22 3.43-1.59 4.34-3.41c.17-.35.51-.56.9-.56h5.53c.38 0 .72.21.89.55c.9 1.8 1.99 3.19 4.34 3.41v.03c0 4.42-3.59 8.01-8 8.01");
}

</style>
