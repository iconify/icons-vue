<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bk0wc9bwk"/><path class="i5lvicvhn"/><path class="xcok15bww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-caret-left-two-tone" /></template>
<style>
.bk0wc9bwk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 6C22 3.79086 20.2091 2 18 2H6C3.79086 2 2 3.79086 2 6V18C2 20.2091 3.79086 22 6 22H18C20.2091 22 22 20.2091 22 18V6Z");
  stroke: none;
}

.i5lvicvhn {
  d: path("M6 3L18 3C19.6569 3 21 4.3431 21 6L21 18C21 19.6569 19.6569 21 18 21L6 21C4.3431 21 3 19.6569 3 18L3 6C3 4.3431 4.3431 3 6 3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xcok15bww {
  d: path("M7.77326 12.4699L15.7107 16.9316C16.0648 17.1306 16.5 16.8716 16.5 16.4617V7.5383C16.5 7.12844 16.0648 6.86937 15.7107 7.06842L7.77326 11.5301C7.40891 11.7349 7.40891 12.2651 7.77326 12.4699Z");
}

</style>
