<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pz3hy5bzx"/><path class="ahl6c4uri"/><path class="inw1qdd8j"/><path class="mzvcb5byi"/><path class="z3zttqj_r"/><path class="a_gwgkc5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speculative-decode-duotone-thin" /></template>
<style>
.a_gwgkc5a {
  d: path("m16 17 2 2 4 -4");
}

.ahl6c4uri {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 6 6 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.inw1qdd8j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 17 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mzvcb5byi {
  d: path("m3 6 6 6 -6 6");
}

.pz3hy5bzx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 6 6 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z3zttqj_r {
  d: path("m10 6 6 6 -6 6");
}

</style>
