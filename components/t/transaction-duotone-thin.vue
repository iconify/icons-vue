<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fa8lp8ket"/><path class="ukyojkvtr"/><path class="d6uto1vti"/><path class="e8rfc8bkg"/><path class="to02llleg"/><path class="jroakeb3a"/><path class="l0zc9ibud"/><path class="mvm7r4bea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transaction-duotone-thin" /></template>
<style>
.d6uto1vti {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 10h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e8rfc8bkg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fa8lp8ket {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 4H3v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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

.to02llleg {
  d: path("M7 4H3v16h4");
}

.ukyojkvtr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
