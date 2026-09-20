<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5v54kp1e"/><path class="wog2376vd"/><path class="lwg_dqcsl"/><path class="ri2m-q_tv"/><path class="l0zc9ibud"/><path class="b8lx3dhmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:traffic-split-duotone-regular" /></template>
<style>
.b8lx3dhmf {
  d: path("M8 14h4");
}

.l0zc9ibud {
  d: path("M8 10h8");
}

.lwg_dqcsl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n5v54kp1e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.wog2376vd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 10h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
