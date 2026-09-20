<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l9cwghw2u"/><path class="q-dmr8bbq"/><path class="ix51aqbzd"/><path class="mrzdbhb5c"/><path class="xbbf36buj"/><path class="y4tlj9bad"/><path class="w8gxvdb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:room-key-duotone-regular" /></template>
<style>
.ix51aqbzd {
  d: path("M3.5 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.l9cwghw2u {
  fill: currentColor;
  d: path("M3.5 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mrzdbhb5c {
  d: path("M7 13.5V21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-dmr8bbq {
  fill: currentColor;
  d: path("M12 5h9v6h-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w8gxvdb9g {
  d: path("M14 8h5");
}

.xbbf36buj {
  d: path("M7 18h4");
}

.y4tlj9bad {
  d: path("M12 5h9v6h-9Z");
}

</style>
