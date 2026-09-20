<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iqxmkybol"/><path class="xedmbxbzm"/><path class="tr6mw0eac"/><path class="jwnes9bsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:webcam-outline-regular" /></template>
<style>
.iqxmkybol {
  d: path("M7 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.jwnes9bsk {
  d: path("M8 19h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tr6mw0eac {
  d: path("M12 15v4");
}

.xedmbxbzm {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
