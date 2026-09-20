<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r8i8nbbml"/><path class="o8-8aibsp"/><path class="wj8ybccjk"/><path class="rkid2r5ui"/><path class="owl9kub7f"/><path class="sjde2nyhb"/><path class="vd0jm7r_j"/><path class="r7xk8o29f"/><path class="gsl5knvuq"/><path class="p0o5ir5ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-columns-duotone-thin" /></template>
<style>
.gsl5knvuq {
  d: path("M15 8h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8-8aibsp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.owl9kub7f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p0o5ir5ue {
  d: path("M15 16h6");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.r8i8nbbml {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rkid2r5ui {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sjde2nyhb {
  d: path("M3 8h6");
}

.vd0jm7r_j {
  d: path("M3 16h6");
}

.wj8ybccjk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
