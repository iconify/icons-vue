<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="etl76_28z"/><path class="t5oi8bw4w"/><path class="fm-6bpbzd"/><path class="s-u1j5bti"/><path class="k7npzjf1o"/><path class="sl2z8ub9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pollution-duotone-regular" /></template>
<style>
.etl76_28z {
  fill: currentColor;
  d: path("M5 21v-9h5v9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fm-6bpbzd {
  d: path("M5 21v-9h5v9Z");
}

.k7npzjf1o {
  d: path("M7.5 12a3 3 0 0 1 0 -6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-u1j5bti {
  d: path("M14 21v-6h5v6Z");
}

.sl2z8ub9q {
  d: path("M7.5 2a3 3 0 0 1 0 6");
}

.t5oi8bw4w {
  fill: currentColor;
  d: path("M14 21v-6h5v6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
