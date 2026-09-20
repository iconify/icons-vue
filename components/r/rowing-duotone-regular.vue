<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nhdek5nuo"/><path class="eapwvqbey"/><path class="dui-9ojgu"/><path class="q5jw2tb7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rowing-duotone-regular" /></template>
<style>
.dui-9ojgu {
  d: path("M7 12 3 8");
}

.eapwvqbey {
  d: path("M3 13h18c-1 4 -4 7 -9 7s-8 -3 -9 -7");
}

.nhdek5nuo {
  fill: currentColor;
  d: path("M3 13h18c-1 4 -4 7 -9 7s-8 -3 -9 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q5jw2tb7h {
  d: path("m17 12 4 -4");
}

</style>
