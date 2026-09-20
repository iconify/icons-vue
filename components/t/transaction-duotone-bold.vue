<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nqxc61b9f"/><path class="zumcy7bta"/><path class="h5jfupb3k"/><path class="gtj8b-brg"/><path class="to02llleg"/><path class="jroakeb3a"/><path class="l0zc9ibud"/><path class="mvm7r4bea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transaction-duotone-bold" /></template>
<style>
.gtj8b-brg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h5jfupb3k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 10h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jroakeb3a {
  d: path("M17 4h4v16h-4");
}

.l0zc9ibud {
  d: path("M8 10h8");
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.nqxc61b9f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4H3v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.to02llleg {
  d: path("M7 4H3v16h4");
}

.zumcy7bta {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
