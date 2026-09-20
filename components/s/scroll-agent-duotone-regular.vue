<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vui6pl4gr"/><path class="ocgq8oo_l"/><path class="ivxytsbkz"/><path class="bbcwxvblg"/><path class="w1fvqnt0l"/><path class="gtsw5xviq"/><path class="nkj1px1_f"/><path class="cfv90ubkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scroll-agent-duotone-regular" /></template>
<style>
.bbcwxvblg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 16.5 17 19l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cfv90ubkl {
  d: path("M14.5 16.5 17 19l2.5 -2.5");
}

.gtsw5xviq {
  d: path("M17 5v14");
}

.ivxytsbkz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 7.5 17 5l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nkj1px1_f {
  d: path("M14.5 7.5 17 5l2.5 2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ocgq8oo_l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vui6pl4gr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w1fvqnt0l {
  d: path("M9.69 8.37a4 4 0 1 1 -3.38 0");
}

</style>
