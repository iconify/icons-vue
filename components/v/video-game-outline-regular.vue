<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mprhlt90i"/><path class="yb9iu4bmw"/><path class="ffs26fbkv"/><path class="wneoubc6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:video-game-outline-regular" /></template>
<style>
.ffs26fbkv {
  d: path("M12 17v4");
}

.mprhlt90i {
  d: path("M3 4v13h18V4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wneoubc6n {
  d: path("M7 21h10");
}

.yb9iu4bmw {
  d: path("M9 8h6v5H9Z");
}

</style>
