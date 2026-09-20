<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="qnvjj7b8l"/><path class="fa1n3u56m"/><path class="xjy454b9k"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="sfjortb-o"/><path class="ucuiysazu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:milestone-goal-duotone-regular" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.fa1n3u56m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qlvopac9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qnvjj7b8l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sfjortb-o {
  d: path("M12 7v5");
}

.ucuiysazu {
  d: path("M9.5 9.5 12 12l2.5 -2.5");
}

.xjy454b9k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 9.5 12 12l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
