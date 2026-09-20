<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p8x8olrmk"/><path class="vzfmp7bra"/><path class="dzjfbdtqu"/><path class="ksls36zfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:party-clean-up-outline-regular" /></template>
<style>
.dzjfbdtqu {
  d: path("m6 5 3 3");
}

.ksls36zfl {
  d: path("m18 4 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8x8olrmk {
  d: path("M7 11v9h10v-9");
}

.vzfmp7bra {
  d: path("M5 11h14");
}

</style>
