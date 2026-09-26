<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="uvxt62y7h"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uvxt62y7h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M17.4296 17.4296L12.75 22.6667C12.5556 22.8788 12.2846 23 12 23C11.7154 23 11.4444 22.8788 11.2546 22.6667L5.2918 16C3.8159 14.35 3 12.2138 3 10C3 8.03 3.6361 6.1987 4.7146 4.7146L17.4296 17.4296ZM6.9035 2.6608C8.3691 1.6207 10.135 1 12 1C16.8325 1 21 5.1675 21 10C21 11.7901 20.4072 13.6433 19.382 15.1393ZM12 7.7573C12 7.7573 12 7.7573 12 7.7573C13.2386 7.7573 14.2427 8.7614 14.2427 10Z");
  stroke: none;
}

</style>
