<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ded97twic"/><path class="o_lgmdh9h"/><path class="bpco9rrox"/><path class="mnswn9nsk"/><path class="wjqx41ynh"/><path class="kamdbib6v"/><path class="pmuiqo95v"/><path class="kt4_ogrrr"/><path class="hgjyjobhk"/><path class="gvpticbjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:waist-measure-duotone-bold" /></template>
<style>
.bpco9rrox {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ded97twic {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gvpticbjc {
  d: path("M18 7v4");
}

.hgjyjobhk {
  d: path("M12 7v4");
}

.kamdbib6v {
  d: path("M2 7h20");
}

.kt4_ogrrr {
  d: path("M6 7v4");
}

.mnswn9nsk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o_lgmdh9h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 17h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wjqx41ynh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
