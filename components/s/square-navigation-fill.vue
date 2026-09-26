<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ttm7-_bye"/><path class="whvi3zb9k"/><path class="r0twj-bzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-navigation-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r0twj-bzb {
  d: path("M8.61484 18.0691L11.2224 12.9948C11.5613 12.3351 12.4387 12.3351 12.7776 12.9948L15.3852 18.0691C15.7728 18.8235 15.1164 19.7053 14.3519 19.4574L12.2556 18.7775C12.0889 18.7234 11.9111 18.7234 11.7444 18.7775L9.64808 19.4574C8.88356 19.7053 8.2272 18.8235 8.61484 18.0691Z");
}

.ttm7-_bye {
  d: path("M20 21C20.5523 21 21 20.5523 21 20V6C21 4.34315 19.6569 3 18 3H6C4.34315 3 3 4.34315 3 6V20C3 20.5523 3.44772 21 4 21");
}

.whvi3zb9k {
  fill: currentColor;
  d: path("M8.61484 18.0691L11.2224 12.9948C11.5613 12.3351 12.4387 12.3351 12.7776 12.9948L15.3852 18.0691C15.7728 18.8235 15.1164 19.7053 14.3519 19.4574L12.2556 18.7775C12.0889 18.7234 11.9111 18.7234 11.7444 18.7775L9.64808 19.4574C8.88356 19.7053 8.2272 18.8235 8.61484 18.0691Z");
  stroke: none;
}

</style>
