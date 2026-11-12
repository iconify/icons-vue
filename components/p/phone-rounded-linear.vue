<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="im7ue1byo"/><path class="ilw--hcrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-rounded-linear" /></template>
<style>
.ilw--hcrz {
  d: path("M7.66774 16.3323C10.9183 19.5829 14.1588 20.0658 16.067 19.9934C17.2004 19.9505 18.2258 19.2992 19.0628 18.4622C20.4558 17.0692 20.2686 14.8468 18.6839 13.9624L17.5209 13.3134C16.4715 12.7277 15.0947 12.9628 14.1722 13.8853C14.1722 13.8853 13.0533 15.0042 11.0246 12.9755C8.99582 10.9467 10.1147 9.8278 10.1147 9.8278C11.0372 8.90533 11.2723 7.52858 10.6866 6.4791L10.0376 5.31617C9.15321 3.73144 6.9308 3.54428 5.53785 4.93723C4.70084 5.77423 4.04956 6.7996 4.00659 7.93309");
}

.im7ue1byo {
  d: path("M7.6677 16.3323C4.41713 13.0817 3.93421 9.84124 4.00655 7.93311");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
