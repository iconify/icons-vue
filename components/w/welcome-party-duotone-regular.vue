<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y8h-esezl"/><path class="r-7kfkbtt"/><path class="b7f-z_e-v"/><path class="urnabiiwt"/><path class="fxaerfbaz"/><path class="naf5gjb6k"/><path class="e0fatccfd"/><path class="cjddu477a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:welcome-party-duotone-regular" /></template>
<style>
.b7f-z_e-v {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cjddu477a {
  d: path("m20 10 -2 2 2 2");
}

.e0fatccfd {
  d: path("M18 12h4");
}

.fxaerfbaz {
  d: path("M6 20V4h10v16");
}

.naf5gjb6k {
  d: path("M12 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r-7kfkbtt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 20V4h10v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.urnabiiwt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m20 10 -2 2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y8h-esezl {
  fill: currentColor;
  d: path("M12 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
