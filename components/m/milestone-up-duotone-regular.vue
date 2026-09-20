<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="qnvjj7b8l"/><path class="tajag26qi"/><path class="n_rzu920n"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="tguw93wue"/><path class="mepcfzh1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:milestone-up-duotone-regular" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.mepcfzh1h {
  d: path("m10 12.5 2 -2 2 2");
}

.n_rzu920n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 12.5 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.tajag26qi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 9.5 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tguw93wue {
  d: path("m10 9.5 2 -2 2 2");
}

</style>
