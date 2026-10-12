<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="l4kye0vgc"/><circle class="rdo2hgb7w"/><path class="tp0wa0tss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rangoli" /></template>
<style>
.l4kye0vgc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.57 3.57l1.25 1.83q.57.83 1.56.64l2.18-.4q.98-.18.8.8l-.4 2.18q-.19.99.64 1.56l1.83 1.25q.82.57 0 1.14l-1.83 1.25q-.83.57-.64 1.56l.4 2.18q.18.98-.8.8l-2.18-.4q-.99-.19-1.56.64l-1.25 1.83q-.57.82-1.14 0l-1.25-1.83q-.57-.83-1.56-.64l-2.18.4q-.98.18-.8-.8l.4-2.18q.19-.99-.64-1.56l-1.83-1.25q-.82-.57 0-1.14l1.83-1.25q.83-.57.64-1.56l-.4-2.18q-.18-.98.8-.8l2.18.4q.99.19 1.56-.64l1.25-1.83q.57-.82 1.14 0");
}

.rdo2hgb7w {
  cx: 12px;
  cy: 12px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tp0wa0tss {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.75h.01M12 17.25h.01M6.75 12h.01m10.49 0h.01M8.3 8.3h.01m7.39 0h.01M8.3 15.7h.01m7.39 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
