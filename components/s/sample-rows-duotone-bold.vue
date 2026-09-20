<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="spgu4hbor"/><path class="zxxlzlquy"/><path class="buiveunpk"/><path class="f4t_kxipe"/><path class="memo7fkja"/><path class="v5el5acla"/><path class="rq7ulnb_u"/><path class="a-yudr8sp"/><path class="t6gygp83h"/><path class="qml5wxbjt"/><path class="ba_uovbta"/><path class="bz2_dqbae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sample-rows-duotone-bold" /></template>
<style>
.a-yudr8sp {
  d: path("M8 9.5h13");
}

.ba_uovbta {
  d: path("M3.5 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.buiveunpk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bz2_dqbae {
  d: path("M3.5 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.f4t_kxipe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 9.5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.memo7fkja {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 15.5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qml5wxbjt {
  d: path("M8 21h13");
}

.rq7ulnb_u {
  d: path("M8 4h13");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
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

.v5el5acla {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 21h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zxxlzlquy {
  fill: currentColor;
  d: path("M3.5 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
