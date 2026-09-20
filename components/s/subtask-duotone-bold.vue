<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="ptvzd8j5m"/><path class="k5u1j4zsh"/><path class="xgrfb-bqu"/><path class="wwnbqi33p"/><path class="nu1_4q-9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:subtask-duotone-bold" /></template>
<style>
.k5u1j4zsh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 16h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nu1_4q-9l {
  d: path("M14 16h7");
}

.ptvzd8j5m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10v6h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wwnbqi33p {
  d: path("M6 10v6h5");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
