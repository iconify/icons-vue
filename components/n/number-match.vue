<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j06mlx6pi"/><g class="y9tr6bcfx"><circle class="h2o1oactl"/><path class="plns88bta"/></g><g class="y9tr6bcfx"><circle class="jj47fcdtq"/><path class="ug3lb5b8x"/></g><path class="h0-791bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:number-match" /></template>
<style>
.h0-791bdi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.105 11.116a1.962 1.962 0 0 1 3.91-.22c.06.62-.135 1.23-.563 1.606c-.794.696-3.347 2.572-3.347 2.572h3.92m9.041-.499c.409.342.85.499 1.84.499h.231a1.479 1.479 0 1 0 0-2.958M35.066 9.65c.41-.34.85-.496 1.841-.493h.23a1.479 1.479 0 1 1 0 2.958M24.049 36.25a1.48 1.48 0 0 0 0 2.959h.962a1.48 1.48 0 0 0 0-2.959m-.001 0a1.48 1.48 0 0 0 0-2.959h-.961a1.48 1.48 0 0 0 0 2.959m0 0h.962");
}

.h2o1oactl {
  cx: 12.357px;
  cy: 23.184px;
  r: 1.96px;
}

.j06mlx6pi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.003 5.5v37m12.868-37v37M42.5 30.459h-37m37-12.869h-37m5.653-7.628l1.48-.806v5.918m10.673 12.067l3.184-5.917h-3.92m13.511 17.985l3.184-5.918h-3.92m.736-6.15l3.184-5.917h-3.92");
}

.jj47fcdtq {
  cx: 12.357px;
  cy: 35.251px;
  r: 1.96px;
}

.plns88bta {
  d: path("M10.57 26.42c.327.427.825.721 1.65.721h.137a1.96 1.96 0 0 0 1.96-1.96v-1.997");
}

.ug3lb5b8x {
  d: path("M10.57 38.487c.327.428.825.722 1.65.722h.137a1.96 1.96 0 0 0 1.96-1.96V35.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
