<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lxbz0e66a"/><path class="lz1dchbpw"/><path class="t3q47sbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-remove-before-duotone" /></template>
<style>
.lxbz0e66a {
  stroke-opacity: 0.4;
  d: path("M4.1716 19C4.5954 20.1986 5.7287 21 7 21L13 21M13 3L7 3C5.7287 3 4.5954 3.8014 4.1716 5");
}

.lz1dchbpw {
  fill: currentColor;
  d: path("M12 22L12 2L19 2C21.2091 2 23 3.7909 23 6L23 18C23 20.2091 21.2091 22 19 22L12 22Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t3q47sbvp {
  d: path("M2 9L8 15M8 9L2 15");
}

</style>
