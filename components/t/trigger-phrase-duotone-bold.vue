<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ifv686bkf"/><path class="gk4tkyb3i"/><path class="zc9k97b5s"/><path class="i9hgspbqe"/><path class="wb0w7r_ye"/><path class="w2flskbzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-phrase-duotone-bold" /></template>
<style>
.gk4tkyb3i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i9hgspbqe {
  d: path("M6 4v3");
}

.ifv686bkf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w2flskbzg {
  d: path("m15 10 -4 4h3l-4 4");
}

.wb0w7r_ye {
  d: path("M9.5 4v3");
}

.zc9k97b5s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 10 -4 4h3l-4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
