<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="lt5o_jbwp"/><path class="tonojwfes"/><path class="b5dtkqn-k"/><path class="sgd11y54u"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p4gh801hs"/><path class="qui36tb8q"/><path class="ygselab1a"/><path class="plvacbczu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rollup-metric-duotone-regular" /></template>
<style>
.b5dtkqn-k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lt5o_jbwp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.p4gh801hs {
  d: path("M8 14v4");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plvacbczu {
  d: path("M18 7v11");
}

.qui36tb8q {
  d: path("M11 12v6");
}

.r3faxubne {
  d: path("M4 4v16");
}

.sgd11y54u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tonojwfes {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ygselab1a {
  d: path("M14 15v3");
}

</style>
