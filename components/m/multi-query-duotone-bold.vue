<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="n7jtegbzu"/><path class="xf6rxlb8o"/><path class="fc8gspe8z"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="gjllsvbkd"/><path class="g-zzhsbrv"/><path class="r_4k1sbsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multi-query-duotone-bold" /></template>
<style>
.fc8gspe8z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.g-zzhsbrv {
  d: path("M7 10h6");
}

.gjllsvbkd {
  d: path("M7 7h6");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.n7jtegbzu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plw-owhdh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r_4k1sbsg {
  d: path("M7 13h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
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
