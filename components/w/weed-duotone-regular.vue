<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v8r1mubbr"/><path class="qkxug8bti"/><path class="krbcqbb8h"/><path class="rrwm8uaph"/><path class="j2d9j4b0r"/><path class="miurf-h0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weed-duotone-regular" /></template>
<style>
.j2d9j4b0r {
  d: path("M12 12 8 8h4L8 4");
}

.krbcqbb8h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 18h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.miurf-h0g {
  d: path("M5 18h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qkxug8bti {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12 8 8h4L8 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rrwm8uaph {
  d: path("M12 4v14");
}

.v8r1mubbr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
