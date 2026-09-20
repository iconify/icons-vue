<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kl0_d31ng"/><path class="qehk_hbbm"/><path class="l4u52cb-r"/><path class="h2-2dgnfu"/><path class="srofgib5x"/><path class="m7gli2e_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trunk-based-duotone-bold" /></template>
<style>
.h2-2dgnfu {
  d: path("M12 3v18");
}

.kl0_d31ng {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l4u52cb-r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 12.5 12 17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m7gli2e_k {
  d: path("M16.5 12.5 12 17");
}

.qehk_hbbm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 6.5 12 11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.srofgib5x {
  d: path("M7.5 6.5 12 11");
}

</style>
