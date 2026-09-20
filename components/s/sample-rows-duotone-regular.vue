<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="spgu4hbor"/><path class="zxxlzlquy"/><path class="dn8u9f3dv"/><path class="vtn3klicd"/><path class="g0-awuehk"/><path class="adoxxhb-n"/><path class="rq7ulnb_u"/><path class="a-yudr8sp"/><path class="t6gygp83h"/><path class="qml5wxbjt"/><path class="ba_uovbta"/><path class="bz2_dqbae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sample-rows-duotone-regular" /></template>
<style>
.a-yudr8sp {
  d: path("M8 9.5h13");
}

.adoxxhb-n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 21h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ba_uovbta {
  d: path("M3.5 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.bz2_dqbae {
  d: path("M3.5 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dn8u9f3dv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g0-awuehk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 15.5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qml5wxbjt {
  d: path("M8 21h13");
}

.rq7ulnb_u {
  d: path("M8 4h13");
}

.spgu4hbor {
  fill: currentColor;
  d: path("M3.5 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.t6gygp83h {
  d: path("M8 15.5h13");
}

.vtn3klicd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9.5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zxxlzlquy {
  fill: currentColor;
  d: path("M3.5 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
