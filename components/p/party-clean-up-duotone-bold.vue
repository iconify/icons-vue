<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aqcyruc0f"/><path class="u-xjqw_1i"/><path class="cwrwyih9j"/><path class="xd1kw_7hv"/><path class="p8x8olrmk"/><path class="vzfmp7bra"/><path class="dzjfbdtqu"/><path class="ksls36zfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:party-clean-up-duotone-bold" /></template>
<style>
.aqcyruc0f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 11v9h10v-9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cwrwyih9j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dzjfbdtqu {
  d: path("m6 5 3 3");
}

.ksls36zfl {
  d: path("m18 4 3 3");
}

.p8x8olrmk {
  d: path("M7 11v9h10v-9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u-xjqw_1i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vzfmp7bra {
  d: path("M5 11h14");
}

.xd1kw_7hv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 4 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
