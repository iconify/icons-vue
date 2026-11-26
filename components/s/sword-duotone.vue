<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ult4xun8r"/><path class="e0fuhacln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sword-duotone" /></template>
<style>
.e0fuhacln {
  d: path("M3 14L10 21M6.5 17.5L3 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ult4xun8r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.7322 14.318L9.4022 9.648L14.7794 4.2709C15.2184 3.8317 15.7538 3.5009 16.3428 3.3045L20.0257 2.077C20.6105 1.8821 21.1905 2.0692 21.5607 2.4393C21.9308 2.8095 22.1179 3.3895 21.923 3.9743L20.6955 7.6571C20.4991 8.2462 20.1683 8.7816 19.729 9.2207L9.682 19.2678L7.2071 16.793Z");
  stroke: none;
}

</style>
