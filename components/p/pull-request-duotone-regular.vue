<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qecovn3xi"/><path class="st2iv5bfu"/><path class="v0qqs_b9c"/><path class="qhv3-tjas"/><path class="v2sxlfbbm"/><path class="kn0tcm93r"/><path class="xaitxdbcw"/><path class="brze8vkpt"/><path class="pw61xnbei"/><path class="e3ixvub0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pull-request-duotone-regular" /></template>
<style>
.brze8vkpt {
  d: path("M18 5v11.5");
}

.e3ixvub0q {
  d: path("m15 8 3 -3 3 3");
}

.kn0tcm93r {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pw61xnbei {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qecovn3xi {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qhv3-tjas {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 5v11.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.st2iv5bfu {
  fill: currentColor;
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v0qqs_b9c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 7.5V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v2sxlfbbm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 8 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xaitxdbcw {
  d: path("M6 7.5V21");
}

</style>
