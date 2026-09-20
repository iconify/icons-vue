<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w31vd-njw"/><path class="ynyobdc9w"/><path class="ewqt22bbd"/><path class="r5roctbum"/><path class="z_j864liq"/><path class="hx7cfzbbm"/><path class="l6rp-_-ny"/><path class="mww7ccc2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:whisk-duotone-regular" /></template>
<style>
.ewqt22bbd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 21c0 -6 1 -12 2 -12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hx7cfzbbm {
  d: path("M6 21c0 -6 2 -12 6 -12s6 6 6 12");
}

.l6rp-_-ny {
  d: path("M10 21c0 -6 1 -12 2 -12");
}

.mww7ccc2b {
  d: path("M14 21c0 -6 -1 -12 -2 -12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r5roctbum {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 21c0 -6 -1 -12 -2 -12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w31vd-njw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ynyobdc9w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 21c0 -6 2 -12 6 -12s6 6 6 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z_j864liq {
  d: path("M12 2v7");
}

</style>
