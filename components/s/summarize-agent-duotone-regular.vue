<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ckyb-n3td"/><path class="r5i32t25p"/><path class="yae9epb6o"/><path class="xwwzgkuou"/><path class="pxx-spbdi"/><path class="pi0o-3bfc"/><path class="ifhv18rgk"/><path class="t_kadbb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:summarize-agent-duotone-regular" /></template>
<style>
.ckyb-n3td {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ifhv18rgk {
  d: path("M12 12h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pi0o-3bfc {
  d: path("M12 7h9");
}

.pxx-spbdi {
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
}

.r5i32t25p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t_kadbb9f {
  d: path("M12 17h3");
}

.xwwzgkuou {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 17h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yae9epb6o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
