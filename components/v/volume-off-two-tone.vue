<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ezd6lzbxv"/><path class="b5bf5sbnp"/><path class="hs6tp-s_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-off-two-tone" /></template>
<style>
.b5bf5sbnp {
  stroke-opacity: 0.4;
  d: path("M15.8044 6.9091C17.2058 8.2316 18 10.0732 18 12C18 12.112 17.9973 12.2238 17.992 12.3351M18.5498 4C20.7519 6.0782 22 8.9721 22 12C22 13.2746 21.7788 14.5254 21.3585 15.7016");
}

.ezd6lzbxv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 12V18.9962C12 20.9544 9.4772 21.746 8.3585 20.1388L5.4777 16H3C1.8954 16 1 15.1046 1 14V10C1 8.8954 1.8954 8 3 8H5.4777L6.5128 6.5128L12 12Z");
  stroke: none;
}

.hs6tp-s_w {
  d: path("M11 11V18.9962C11 19.9753 9.7386 20.3711 9.1793 19.5675L6.2984 15.4287C6.1115 15.1601 5.8049 15 5.4777 15H3C2.4477 15 2 14.5523 2 14V10C2 9.4477 2.4477 9 3 9H5.4777C5.8049 9 6.1115 8.8399 6.2984 8.5713L7.2312 7.2312M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
