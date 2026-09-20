<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vuatpzs-r"/><path class="p2t15zbfd"/><path class="coau-6byh"/><path class="jvij24bfq"/><path class="j0x-itbqz"/><path class="iaj8d8bgd"/><path class="w_4k9q5tv"/><path class="m__qgi9_a"/><path class="nhzanrbsp"/><path class="r8i1ojbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sequential-test-duotone-regular" /></template>
<style>
.coau-6byh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17.5 7 3.5 3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iaj8d8bgd {
  d: path("m3 8 2 2 3 -3");
}

.j0x-itbqz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jvij24bfq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 7 -3.5 3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m__qgi9_a {
  d: path("m17.5 7 3.5 3.5");
}

.nhzanrbsp {
  d: path("m21 7 -3.5 3.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p2t15zbfd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 8 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r8i1ojbwn {
  d: path("M3 16.5h18");
}

.vuatpzs-r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 8 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w_4k9q5tv {
  d: path("m10 8 2 2 3 -3");
}

</style>
