<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG9lT6MdIi)" class="h7yeo2xyf"/><path fill="url(#SVGPI89fceT)" class="qlaiqqb9l"/><path class="yoqdsabrl"/><defs><linearGradient id="SVG9lT6MdIi" x1="19.031" x2="3.736" y1="11.485" y2="15.06" gradientUnits="userSpaceOnUse"><stop class="tvpuj8b9x"/><stop offset="1" class="e5ca-0brc"/></linearGradient><linearGradient id="SVGPI89fceT" x1="26.062" x2="6.373" y1="14.578" y2="14.763" gradientUnits="userSpaceOnUse"><stop offset=".36" class="bg2rzdb_t"/><stop offset=".66" class="yh2fp-dwt"/><stop offset="1" class="y0lk_ibnw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:qrdo" /></template>
<style>
.bg2rzdb_t {
  stop-color: var(--svg-color--ff26eb, #ff26eb);
}

.e5ca-0brc {
  stop-color: var(--svg-color--ffe000, #ffe000);
}

.ft5dv1b6b {
  fill: none;
}

.h7yeo2xyf {
  d: path("M12 5.81a6.188 6.188 0 0 0-6.064 7.424a1.406 1.406 0 1 1-2.756.563a9 9 0 1 1 17.82-1.8h-2.813A6.19 6.19 0 0 0 12 5.809");
}

.qlaiqqb9l {
  d: path("M19.2 9.186a1.407 1.407 0 0 1 1.643 1.125q.157.831.157 1.677v.005c0 2.295-.86 4.388-2.273 5.98l.546.658a1.407 1.407 0 0 1-2.171 1.788l-.546-.663a9 9 0 0 1-12.342-3.248A9 9 0 0 1 3 11.993h2.813a6.187 6.187 0 0 0 8.92 5.552l-.82-.996a1.405 1.405 0 0 1 .19-1.98a1.407 1.407 0 0 1 1.98.192l.833 1.007a6.16 6.16 0 0 0 1.17-4.933a1.406 1.406 0 0 1 1.12-1.643z");
}

.tvpuj8b9x {
  stop-color: var(--svg-color--2dde41, #2dde41);
}

.y0lk_ibnw {
  stop-color: var(--svg-color--27b3f9, #27b3f9);
}

.yh2fp-dwt {
  stop-color: var(--svg-color--137ff9, #137ff9);
}

.yoqdsabrl {
  fill: var(--svg-color--ffe000, #ffe000);
  d: path("M5.83 12.47a7 7 0 0 0 .106.765a1.406 1.406 0 0 1-2.756.562a9 9 0 0 1-.18-1.8h2.813");
}

</style>
