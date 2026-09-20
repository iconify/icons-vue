<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hpm6v1-ys"/><path class="plkicdbsg"/><path class="sabwsnbru"/><path class="o6x5ysbmt"/><path class="nbz__qqtx"/><path class="jkuojibnm"/><path class="d1du4rxru"/><path class="a9cczt5un"/><path class="t3w_facee"/><path class="j4if4rbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:softmax-duotone-bold" /></template>
<style>
.a9cczt5un {
  d: path("M10 8v12");
}

.d1du4rxru {
  d: path("M6 14v6");
}

.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j4if4rbfv {
  d: path("M18 14v6");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.nbz__qqtx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o6x5ysbmt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 3v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plkicdbsg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sabwsnbru {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t3w_facee {
  d: path("M14 3v17");
}

</style>
