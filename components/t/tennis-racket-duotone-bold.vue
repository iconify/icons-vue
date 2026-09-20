<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="smo8q7bln"/><path class="nb3ovlbtz"/><path class="bjcflih-f"/><path class="kf3i57zot"/><path class="ffs26fbkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tennis-racket-duotone-bold" /></template>
<style>
.bjcflih-f {
  d: path("M9 5v10");
}

.ffs26fbkv {
  d: path("M12 17v4");
}

.kf3i57zot {
  d: path("M15 5v10");
}

.nb3ovlbtz {
  d: path("M12 3c4 0 7 3 7 7s-3 7 -7 7 -7 -3 -7 -7 3 -7 7 -7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.smo8q7bln {
  fill: currentColor;
  d: path("M12 3c4 0 7 3 7 7s-3 7 -7 7 -7 -3 -7 -7 3 -7 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
