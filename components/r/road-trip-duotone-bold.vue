<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ayqrtc2-a"/><path class="zll-_89wk"/><path class="v9n4_syfk"/><path class="znsvcwp8w"/><path class="t1w08ccuz"/><path class="g7ipnac6i"/><path class="icp673bbo"/><path class="pa9quik2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:road-trip-duotone-bold" /></template>
<style>
.ayqrtc2-a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 20 6 -6V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g7ipnac6i {
  d: path("m21 20 -6 -6V5");
}

.icp673bbo {
  d: path("M12 9v3");
}

.pa9quik2g {
  d: path("M12 16v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t1w08ccuz {
  d: path("m3 20 6 -6V5");
}

.v9n4_syfk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zll-_89wk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21 20 -6 -6V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.znsvcwp8w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 16v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
