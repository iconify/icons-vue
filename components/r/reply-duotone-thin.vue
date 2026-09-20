<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h-d1yibvp"/><path class="icjgng4dc"/><path class="pzovgl99o"/><path class="q5w-xob0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reply-duotone-thin" /></template>
<style>
.h-d1yibvp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4 3 9l5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icjgng4dc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h14v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pzovgl99o {
  d: path("M8 4 3 9l5 5");
}

.q5w-xob0a {
  d: path("M3 9h14v11");
}

</style>
