<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bucfw6bdg"/><path class="qy44fxbnk"/><path class="n2z2bb1zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-calling-rounded-linear" /></template>
<style>
.bucfw6bdg {
  d: path("M14 2C14 2 16.2 2.2 19 5C21.8 7.8 22 10 22 10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n2z2bb1zb {
  d: path("M10.0376 5.31617C9.15317 3.73144 6.93076 3.54428 5.53781 4.93723C4.7008 5.77423 4.04952 6.7996 4.00655 7.93309C3.93421 9.84122 4.41713 13.0817 7.6677 16.3323C10.9183 19.5829 14.1588 20.0658 16.0669 19.9934C17.2004 19.9505 18.2258 19.2992 19.0628 18.4622C20.4557 17.0692 20.2686 14.8468 18.6838 13.9624L17.5209 13.3134C16.4714 12.7277 15.0947 12.9628 14.1722 13.8853C14.1722 13.8853 13.0532 15.0042 11.0245 12.9755C8.99578 10.9467 10.1147 9.8278 10.1147 9.8278C11.0372 8.90533 11.2723 7.52858 10.6866 6.4791L10.0376 5.31617Z");
}

.qy44fxbnk {
  d: path("M14.207 5.53564C14.207 5.53564 15.197 5.81849 16.6819 7.30341C18.1668 8.78834 18.4497 9.77829 18.4497 9.77829");
}

</style>
