<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l65brscyv"/><path class="rsu38odap"/><path class="jeb_6eb2t"/><path class="nqst3jwoj"/><path class="g6dpwlb_r"/><path class="hspeesv2z"/><path class="ujt25lh2u"/><path class="tv6hbrcra"/><path class="p6gr82bvc"/><path class="mu4i3ybkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:raise-goal-duotone-thin" /></template>
<style>
.g6dpwlb_r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 11 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hspeesv2z {
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
}

.jeb_6eb2t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 20.5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l65brscyv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mu4i3ybkf {
  d: path("m10 11 2 -2 2 2");
}

.nqst3jwoj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 8 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p6gr82bvc {
  d: path("m10 8 2 -2 2 2");
}

.rsu38odap {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 15v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tv6hbrcra {
  d: path("M8.5 20.5h7");
}

.ujt25lh2u {
  d: path("M12 15v5.5");
}

</style>
