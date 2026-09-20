<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="u-fiw6o5c"/><path class="ej4mlkbbb"/><path class="y-km_cbaf"/><path class="wm3y1nr6o"/><path class="tr_x2kktf"/><path class="k49-sybxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:marvis" /></template>
<style>
.ej4mlkbbb {
  d: path("M38.788 37.09c.055-1.294 2.016-2.432 4.79-2.976C35.637 32.22 25.058 26.745 24 13.94C22.942 26.745 12.363 32.22 4.422 34.114c2.774.544 4.735 1.682 4.79 2.975");
}

.k49-sybxu {
  d: path("M36.51 21.65a4.27 4.27 0 0 1 4.269-4.27");
}

.tr_x2kktf {
  d: path("M36.51 21.65a4.27 4.27 0 0 0-4.27-4.27m4.27-4.27a4.27 4.27 0 0 0 4.269 4.27");
}

.u-fiw6o5c {
  d: path("M19.227 35.908c2.292-2.07 3.675-4.645 4.773-7.376c1.098 2.731 2.481 5.305 4.773 7.376zm1.238.114v2.972m7.07-2.972v2.972");
}

.wm3y1nr6o {
  d: path("M11.416 31.412L20.63 8.5h6.74l9.214 22.912M36.51 13.11a4.27 4.27 0 0 1-4.27 4.27");
}

.y-km_cbaf {
  d: path("m37.926 35.218l1.628 4.282H33.48l-1.873-4.246C28.97 33.903 24.51 25.922 24 21.544c-.51 4.378-4.97 12.359-7.607 13.71L14.52 39.5H8.446l1.628-4.282");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
