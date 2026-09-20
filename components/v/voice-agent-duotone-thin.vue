<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mbpyd7bth"/><path class="u_5xtyu1s"/><path class="f02t2vblf"/><path class="eyylp2bqm"/><path class="yeuzzbchl"/><path class="coi-np7dk"/><path class="vckqcjbbb"/><path class="pst98pbad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:voice-agent-duotone-thin" /></template>
<style>
.coi-np7dk {
  d: path("M15 9v6");
}

.eyylp2bqm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f02t2vblf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbpyd7bth {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.11 7.47a5 5 0 1 1 -4.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pst98pbad {
  d: path("M21 10v4");
}

.u_5xtyu1s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vckqcjbbb {
  d: path("M18 5v14");
}

.yeuzzbchl {
  d: path("M9.11 7.47a5 5 0 1 1 -4.22 0");
}

</style>
