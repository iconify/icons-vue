<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s-_fctbko"/><path class="yj49v48br"/><path class="of9uamb7y"/><path class="g9aitcb2z"/><path class="l-8pkdhvs"/><path class="xhwe0sbyf"/><path class="ze3hawb4v"/><path class="vdq8lyksd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:queue-depth-duotone-regular" /></template>
<style>
.g9aitcb2z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l-8pkdhvs {
  d: path("M6.5 4H4v16h2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.of9uamb7y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s-_fctbko {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6.5 4H4v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vdq8lyksd {
  d: path("M18 12v6");
}

.xhwe0sbyf {
  d: path("M10 9v9");
}

.yj49v48br {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ze3hawb4v {
  d: path("M14 6v12");
}

</style>
