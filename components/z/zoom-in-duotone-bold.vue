<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="nfad3gbna"/><path class="xf6rxlb8o"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="wj4ljftik"/><path class="g-zzhsbrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:zoom-in-duotone-bold" /></template>
<style>
.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.g-zzhsbrv {
  d: path("M7 10h6");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.nfad3gbna {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 7v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plw-owhdh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wj4ljftik {
  d: path("M10 7v6");
}

.xf6rxlb8o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yjc9h6oua {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
