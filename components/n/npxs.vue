<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="vn8wcdc9j"/><path class="mvtmbztmn"/><path fill="url(#SVG31WVZcSm)" clip-rule="evenodd" class="ivfp-kb5y"/><defs><linearGradient id="SVG31WVZcSm" x1="9.675" x2="16.741" y1="9.76" y2="17.892" gradientUnits="userSpaceOnUse"><stop class="iec-__bqf"/><stop offset="1" class="p1we3jffn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:npxs" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iec-__bqf {
  stop-color: var(--svg-color--1a1e21, #1a1e21);
}

.ivfp-kb5y {
  fill-rule: evenodd;
  d: path("M11.839 8.572L15.267 12l-3.428 3.428L8.397 12zM9.835 12l2.002 1.995L13.832 12l-1.994-1.994z");
}

.mvtmbztmn {
  fill: var(--svg-color--fcd309, #fcd309);
  d: path("m9.115 12.001l2.723-2.711l2.711 2.711l-2.711 2.711z");
}

.p1we3jffn {
  stop-color: var(--svg-color--06060a, #06060a);
}

.vn8wcdc9j {
  fill: var(--svg-color--fcd309, #fcd309);
  fill-rule: evenodd;
  d: path("M12.718 12L21 20.282l-.718.718L12 12.717L3.718 21L3 20.282L11.283 12L3 3.718L3.718 3L12 11.283L20.282 3l.718.718z");
}

</style>
