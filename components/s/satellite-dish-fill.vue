<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u9tnjpbsd"/><path class="s7hl6q8xy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:satellite-dish-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s7hl6q8xy {
  d: path("M9.7778 14.2222L12 12M13.1111 6.4444C15.5657 6.4444 17.5556 8.4343 17.5556 10.8889M13.1111 2C18.0203 2 22 5.9797 22 10.8889");
}

.u9tnjpbsd {
  fill: currentColor;
  d: path("M10.4849 13.5151L15.133 18.1632C15.5289 18.5591 15.7513 19.0961 15.7513 19.656C15.7513 20.3394 15.4206 20.9805 14.8637 21.3766C13.3774 22.4327 11.5993 23.0001 9.776 23.0001C8.3374 23.0001 6.9207 22.6467 5.6506 21.971C2.7875 20.4461 0.999 17.4661 1 14.2222C1 12.3996 1.5673 10.6222 2.6232 9.1367C3.0193 8.5796 3.6605 8.2487 4.344 8.2487C4.9038 8.2487 5.4407 8.471 5.8366 8.8668L10.4849 13.5151Z");
  stroke: none;
}

</style>
