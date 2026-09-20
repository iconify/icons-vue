<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="brpzkcbqq"/><path class="ikpvbwcwg"/><path class="e7f2i2beh"/><path class="nbhxjjbfa"/><path class="ndkxcpb5b"/><path class="qaqzxor9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:snowboard-duotone-bold" /></template>
<style>
.brpzkcbqq {
  fill: currentColor;
  d: path("M6 21C3 18 3 6 6 3c3 3 3 15 0 18");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e7f2i2beh {
  fill: currentColor;
  d: path("M12 6h5v3h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ikpvbwcwg {
  fill: currentColor;
  d: path("M12 16h5v3h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nbhxjjbfa {
  d: path("M6 21C3 18 3 6 6 3c3 3 3 15 0 18");
}

.ndkxcpb5b {
  d: path("M12 16h5v3h-5Z");
}

.qaqzxor9c {
  d: path("M12 6h5v3h-5Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
