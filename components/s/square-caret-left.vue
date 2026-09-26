<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cc50cvs0o"/><path class="xcok15bww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-caret-left" /></template>
<style>
.cc50cvs0o {
  d: path("M6 3H18C19.6569 3 21 4.34315 21 6V18C21 19.6569 19.6569 21 18 21H6C4.34315 21 3 19.6569 3 18V6C3 4.34315 4.34315 3 6 3Z");
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
