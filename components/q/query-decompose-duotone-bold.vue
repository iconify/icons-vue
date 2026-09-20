<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="lcc-b6b9s"/><path class="ympzytb_f"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="d7edxnn1x"/><path class="s00zhtbiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:query-decompose-duotone-bold" /></template>
<style>
.d7edxnn1x {
  d: path("M5.5 10H8l2.5 -2.5H13");
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.lcc-b6b9s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 10H8l2.5 -2.5H13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plw-owhdh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s00zhtbiw {
  d: path("m8 10 2.5 2.5H13");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yjc9h6oua {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ympzytb_f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 10 2.5 2.5H13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
