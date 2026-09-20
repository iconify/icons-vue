<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gap0lacnb"/><path class="c5v_de02i"/><path class="jfcsmebdz"/><path class="kqcu0mbfo"/><path class="ic_pehd5a"/><path class="c8wm-2bna"/><path class="e7aqn3bvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:uv-index-duotone-bold" /></template>
<style>
.c5v_de02i {
  d: path("M7.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.c8wm-2bna {
  d: path("M9 17v4");
}

.e7aqn3bvb {
  d: path("M15 17v4");
}

.gap0lacnb {
  fill: currentColor;
  d: path("M7.5 8a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.jfcsmebdz {
  d: path("m4.5 3.5 3 3");
}

.kqcu0mbfo {
  d: path("m19.5 3.5 -3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
