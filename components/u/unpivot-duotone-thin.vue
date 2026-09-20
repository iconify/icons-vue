<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nr2mcrb0o"/><path class="wpfuevp-t"/><path class="q-8azacde"/><path class="i1jka66ox"/><path class="yd1dd2b-v"/><path class="hsnj9o-9y"/><path class="j4m0w2b-t"/><path class="p3dq04btg"/><path class="i9hpnuf0x"/><path class="z0ud8rb7a"/><path class="ys-dg812g"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:unpivot-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hsnj9o-9y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i1jka66ox {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 10.5 12 13l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i9hpnuf0x {
  d: path("M18 2v5.5");
}

.j4m0w2b-t {
  d: path("M6 2v5.5");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.nr2mcrb0o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 2v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p3dq04btg {
  d: path("M12 2v5.5");
}

.q-8azacde {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 2v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wpfuevp-t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 2v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yd1dd2b-v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

.z0ud8rb7a {
  d: path("M9.5 10.5 12 13l2.5 -2.5");
}

</style>
