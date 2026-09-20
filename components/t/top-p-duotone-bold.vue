<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rdvmv8b4c"/><path class="u2c68cx9n"/><path class="hrrcydb2l"/><path class="l7r9aieyp"/><path class="lcu8k5sld"/><path class="yam3-1b2z"/><path class="sl7vxjbhd"/><path class="pt73j1ikv"/><path class="xa3jgydgh"/><path class="g620qibmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:top-p-duotone-bold" /></template>
<style>
.g620qibmn {
  d: path("M20 17v3");
}

.hrrcydb2l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l7r9aieyp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lcu8k5sld {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 17v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pt73j1ikv {
  d: path("M15 14v6");
}

.rdvmv8b4c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sl7vxjbhd {
  d: path("M10 11v9");
}

.u2c68cx9n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xa3jgydgh {
  d: path("M3 12h9");
}

.yam3-1b2z {
  d: path("M5 8v12");
}

</style>
