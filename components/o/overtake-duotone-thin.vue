<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hb48mmlja"/><path class="r94r72buw"/><path class="n8sts3-0i"/><path class="oje-b6bwm"/><path class="e7rd2wb8e"/><path class="cptzy0tvb"/><path class="hcn-wubvk"/><path class="toy0nxbdm"/><path class="ler50rfbf"/><path class="caiwqabfd"/><path class="qw9zcf0wd"/><path class="beunabbsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:overtake-duotone-thin" /></template>
<style>
.beunabbsv {
  d: path("M12.5 6.5 15 4l2.5 2.5");
}

.caiwqabfd {
  d: path("M6.5 10.5 9 8l2.5 2.5");
}

.cptzy0tvb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.5 6.5 15 4l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e7rd2wb8e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 4v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hb48mmlja {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hcn-wubvk {
  d: path("M3 2v20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ler50rfbf {
  d: path("M9 8v12");
}

.n8sts3-0i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oje-b6bwm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.5 10.5 9 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qw9zcf0wd {
  d: path("M15 4v12");
}

.r94r72buw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.toy0nxbdm {
  d: path("M21 2v20");
}

</style>
