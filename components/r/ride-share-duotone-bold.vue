<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qp882rbfj"/><path class="h03wmtogt"/><path class="yo-dkgbus"/><path class="l4usqt3et"/><path class="y4h9u0bph"/><path class="sqwju3bsh"/><path class="du3agkbjb"/><path class="fquh7rbnp"/><path class="stuivn6rm"/><path class="w3y_atbbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ride-share-duotone-bold" /></template>
<style>
.du3agkbjb {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fquh7rbnp {
  d: path("M15 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.h03wmtogt {
  fill: currentColor;
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l4usqt3et {
  fill: currentColor;
  d: path("M7.5 12.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qp882rbfj {
  fill: currentColor;
  d: path("M2 16V8.5h4L9.5 5h5L18 8.5h4V16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sqwju3bsh {
  d: path("M2 16V8.5h4L9.5 5h5L18 8.5h4V16Z");
}

.stuivn6rm {
  d: path("M7.5 12.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.w3y_atbbp {
  d: path("M12.5 12.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.y4h9u0bph {
  fill: currentColor;
  d: path("M12.5 12.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yo-dkgbus {
  fill: currentColor;
  d: path("M15 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
