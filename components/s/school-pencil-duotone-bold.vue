<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vizcuby0h"/><path class="rxedw8b6o"/><path class="iq9in6bpg"/><path class="wsj78vmsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:school-pencil-duotone-bold" /></template>
<style>
.iq9in6bpg {
  d: path("m7 16 -3 3h6");
}

.rxedw8b6o {
  d: path("m7 16 9 -9 3 3 -9 9Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vizcuby0h {
  fill: currentColor;
  d: path("m7 16 9 -9 3 3 -9 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wsj78vmsl {
  d: path("m14 9 3 3");
}

</style>
