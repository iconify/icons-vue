<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="dvdnlhq9o"/><path class="puu_2kb8j"/><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="vwjk1ok-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transcribe-live-duotone-regular" /></template>
<style>
.dvdnlhq9o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 10h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.mkh6f026t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.puu_2kb8j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h4l2.5 -2.5L12 17l2.5 -2.5L17 17h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vwjk1ok-c {
  d: path("M3 17h4l2.5 -2.5L12 17l2.5 -2.5L17 17h4");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>
