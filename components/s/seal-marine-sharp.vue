<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kb3o8gsuk"/><path class="t2vi0ol3b"/><path class="h439az8vh"/><circle class="qa1vi5bxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seal-marine-sharp" /></template>
<style>
.h439az8vh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 15.5l.75 2.25l2.25.75");
}

.kb3o8gsuk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21.25H3.5V19c0-4 2.5-6 4.75-8.5C9.5 9 9.75 7.5 11 6.75s3 0 3.5 1.25l2 .5l-1.75 1.25c-.75 1.5-2 2.75-2.5 4.5c-.5 2.5 0 4.75 1.5 7Z");
}

.qa1vi5bxv {
  cx: 17.75px;
  cy: 4.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t2vi0ol3b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.25 8.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
