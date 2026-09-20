<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aumzl2y6d"/><path class="ksyn2mbyr"/><path class="hppiisbif"/><path class="e84dr_enj"/><path class="dn1egm5la"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:valley-duotone-thin" /></template>
<style>
.aumzl2y6d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 7 6 6 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dn1egm5la {
  d: path("m10 17 6 -6 6 6");
}

.e84dr_enj {
  d: path("m2 7 6 6 6 -6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hppiisbif {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ksyn2mbyr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 17 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

</style>
