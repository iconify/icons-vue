<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><circle class="c2sgco4gm"/><path class="n271x53ai"/><ellipse class="o77x4q1zh"/><path class="xx_ptjbph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:symphony-alt-1" /></template>
<style>
.c2sgco4gm {
  cx: 23.795px;
  cy: 23.729px;
  r: 5.09px;
}

.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.n271x53ai {
  d: path("M11.135 21.008a13.09 13.09 0 0 1 10.086-9.767m-14.069 8.67A17.12 17.12 0 0 1 19.448 7.368m17.38 19.918a13.09 13.09 0 0 1-10.087 9.767m14.069-8.67a17.12 17.12 0 0 1-12.296 12.544");
}

.o77x4q1zh {
  cx: 8.931px;
  cy: 42.848px;
  rx: 3.338px;
  ry: 2.115px;
}

.xx_ptjbph {
  d: path("M12.261 42.765V28.653m3.999 3.281a3.553 3.553 0 0 1-3.952-3.205M41.245 11.17H32.52l-2.512 2.512");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
