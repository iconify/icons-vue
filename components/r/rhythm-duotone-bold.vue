<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ukc-ymbhf"/><path class="igd9_l93j"/><path class="wsqmw9r_c"/><path class="csq694bnv"/><path class="i_61jzbqt"/><path class="zto18nxmz"/><path class="st-dlsdww"/><path class="i4kf51esh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rhythm-duotone-bold" /></template>
<style>
.csq694bnv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i_61jzbqt {
  d: path("M4 8v8");
}

.i4kf51esh {
  d: path("M19 5v14");
}

.igd9_l93j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.st-dlsdww {
  d: path("M14 8v8");
}

.ukc-ymbhf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wsqmw9r_c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zto18nxmz {
  d: path("M9 5v14");
}

</style>
