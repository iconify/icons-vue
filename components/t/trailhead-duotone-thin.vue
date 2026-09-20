<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ja0_o1hya"/><path class="u2k9_fzjm"/><path class="hppiisbif"/><path class="ftqzjnb8u"/><path class="naxi-2ilz"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trailhead-duotone-thin" /></template>
<style>
.ftqzjnb8u {
  d: path("M6 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hppiisbif {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ja0_o1hya {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.naxi-2ilz {
  d: path("M6 5h10l3.5 3.5L16 12H6");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.u2k9_fzjm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 5h10l3.5 3.5L16 12H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
