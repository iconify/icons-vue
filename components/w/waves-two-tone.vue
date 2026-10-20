<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jh6dc4htq"/><path class="t14gcdbdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:waves-two-tone" /></template>
<style>
.jh6dc4htq {
  d: path("M2 8.5C2.9123 7.5421 4.1772 7 5.5 7C6.8228 7 8.0877 7.5421 9 8.5C9.9123 9.4579 11.1772 10 12.5 10C13.8228 10 15.0877 9.4579 16 8.5C16.9123 7.5421 18.1772 7 19.5 7C20.4 7 21.3 7.25 22 7.7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t14gcdbdw {
  stroke-opacity: 0.4;
  d: path("M2 15.5C2.9123 14.5421 4.1772 14 5.5 14C6.8228 14 8.0877 14.5421 9 15.5C9.9123 16.4579 11.1772 17 12.5 17C13.8228 17 15.0877 16.4579 16 15.5C16.9123 14.5421 18.1772 14 19.5 14C20.4 14 21.3 14.25 22 14.7");
}

</style>
