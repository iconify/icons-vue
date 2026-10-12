<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="uvqndk25q"/><path class="sci58wslm"/><path class="bgq0jqblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pinwheel" /></template>
<style>
.bgq0jqblk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15.25v6");
}

.sci58wslm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9h.01");
}

.uvqndk25q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.39 7.18l.85-3.37q.15-.58.42-.05l1.46 2.89q.27.53-.32.64l-1.97.36q-.59.11-.44-.47m.43 3.21l3.37.85q.58.15.05.42l-2.89 1.46q-.53.27-.64-.32l-.36-1.97q-.11-.59.47-.44m-3.21.43l-.85 3.37q-.15.58-.42.05l-1.46-2.89q-.27-.53.32-.64l1.97-.36q.59-.11.44.47m-.43-3.21l-3.37-.85q-.58-.15-.05-.42l2.89-1.46q.53-.27.64.32l.36 1.97q.11.59-.47.44");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
