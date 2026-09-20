<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z70pbv_vu"/><path class="eucan1bre"/><path class="a2rsdhb4f"/><path class="f5o_v9fiv"/><path class="af7iv3n-p"/><path class="ajxlkdb4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vram-full-outline-bold" /></template>
<style>
.a2rsdhb4f {
  d: path("M12 14v3");
}

.af7iv3n-p {
  d: path("M12 2v2.5");
}

.ajxlkdb4q {
  d: path("M11 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.eucan1bre {
  d: path("M7 14v3");
}

.f5o_v9fiv {
  d: path("M17 14v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z70pbv_vu {
  d: path("M14 11h5a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-3l3 -3h5");
}

</style>
