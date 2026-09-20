<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="ewn3iubfv"/><path class="t1ep0ebko"/><path class="gq5kn0epi"/><path class="xgrfb-bqu"/><path class="he7cpnbxn"/><path class="ky10s_bai"/><path class="ru0la3bku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-wrap-duotone-bold" /></template>
<style>
.ewn3iubfv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gq5kn0epi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.5 12.5 10 15l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.he7cpnbxn {
  d: path("M3 12h14");
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky10s_bai {
  d: path("M17 12v3h-7");
}

.ru0la3bku {
  d: path("M12.5 12.5 10 15l2.5 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t1ep0ebko {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 12v3h-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
