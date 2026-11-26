<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pbczp8bjd"/><path clip-rule="evenodd" class="l1xt40i7j"/><path class="hrmt0jbjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-move-after-duotone" /></template>
<style>
.hrmt0jbjb {
  d: path("M16 12H22M19 9L22 12L19 15");
}

.l1xt40i7j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1 6C1 3.7909 2.7909 2 5 2L12 2L12 22L5 22C2.7909 22 1 20.2091 1 18Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pbczp8bjd {
  stroke-opacity: 0.4;
  d: path("M19.8284 5C19.4046 3.8014 18.2713 3 17 3L11 3M11 21L17 21C18.2713 21 19.4046 20.1986 19.8284 19");
}

</style>
