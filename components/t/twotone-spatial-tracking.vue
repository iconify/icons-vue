<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig9fv2djm"/><path class="zi85cy8yy"/><path class="t9m9xx3tm"/><circle class="wi4da5bgf"/><path class="sd3_h5bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-spatial-tracking" /></template>
<style>
.ig9fv2djm {
  fill: currentColor;
  d: path("M20.05 2.41L18.64 1c-3.51 3.51-3.51 9.21 0 12.73l1.41-1.41c-2.73-2.74-2.73-7.18 0-9.91");
}

.sd3_h5bmg {
  fill: currentColor;
  d: path("M10 13c2.21 0 4-1.79 4-4s-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4m0-6c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m6.39 8.56C14.71 14.7 12.53 14 10 14s-4.71.7-6.39 1.56A2.97 2.97 0 0 0 2 18.22V21h16v-2.78c0-1.12-.61-2.15-1.61-2.66M16 19H4v-.78c0-.38.2-.72.52-.88C5.71 16.73 7.63 16 10 16s4.29.73 5.48 1.34c.32.16.52.5.52.88z");
}

.t9m9xx3tm {
  fill: currentColor;
  d: path("M15.48 17.34C14.29 16.73 12.37 16 10 16s-4.29.73-5.48 1.34c-.32.16-.52.5-.52.88V19h12v-.78c0-.38-.2-.72-.52-.88");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.wi4da5bgf {
  cx: 10px;
  cy: 9px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zi85cy8yy {
  fill: currentColor;
  d: path("m22.88 5.24l-1.41-1.41a5.003 5.003 0 0 0 0 7.07l1.41-1.41a3.01 3.01 0 0 1 0-4.25");
}

</style>
