<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z1ra8bb5p"/><path class="nqxc61b9f"/><path class="zumcy7bta"/><path class="rpyanp93e"/><path class="to02llleg"/><path class="jroakeb3a"/><path class="iup9trbmr"/><path class="u7m7z6ojw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:savepoint-duotone-bold" /></template>
<style>
.iup9trbmr {
  d: path("M12 6v4");
}

.jroakeb3a {
  d: path("M17 4h4v16h-4");
}

.nqxc61b9f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4H3v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rpyanp93e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.to02llleg {
  d: path("M7 4H3v16h4");
}

.u7m7z6ojw {
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.z1ra8bb5p {
  fill: currentColor;
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zumcy7bta {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
