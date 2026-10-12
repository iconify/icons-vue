<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jzlpbys3z"/><path class="xy1ajjbrp"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:suv-car-sharp" /></template>
<style>
.hha4cxblz {
  cx: 17px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzlpbys3z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5v-3l1-.37l1-.38l.42-1.18l1.41-3.89L7 5.5h14.25v11.25H2.75z");
}

.l0haxibzw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 19h.01");
}

.ox2ue_b-w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

.r_0b548wt {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xy1ajjbrp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.17 11.53l.91-2.56l.17-.47h3.25V12H8zM16 8.5h2.5V12h-3V8.5z");
}

</style>
