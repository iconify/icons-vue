<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kwcqdjbyw"/><path class="f_i6-4ffz"/><path class="rex-2ymuk"/><path class="w8m80tbhq"/><path class="g66jkhb9w"/><path class="iaj8d8bgd"/><path class="w_4k9q5tv"/><path class="m__qgi9_a"/><path class="nhzanrbsp"/><path class="r8i1ojbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sequential-test-duotone-thin" /></template>
<style>
.f_i6-4ffz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 8 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g66jkhb9w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iaj8d8bgd {
  d: path("m3 8 2 2 3 -3");
}

.kwcqdjbyw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 8 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m__qgi9_a {
  d: path("m17.5 7 3.5 3.5");
}

.nhzanrbsp {
  d: path("m21 7 -3.5 3.5");
}

.r8i1ojbwn {
  d: path("M3 16.5h18");
}

.rex-2ymuk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17.5 7 3.5 3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w_4k9q5tv {
  d: path("m10 8 2 2 3 -3");
}

.w8m80tbhq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 7 -3.5 3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
