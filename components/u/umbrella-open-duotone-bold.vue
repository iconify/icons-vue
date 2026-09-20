<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hyp6v68rm"/><path class="gk4de-b1j"/><path class="v2mer508z"/><path class="ra0ia6tpa"/><path class="ko52u6bwb"/><path class="l10is9spu"/><path class="wwozeg7ww"/><path class="yih0nfb7c"/><path class="qxhe48bjs"/><path class="evq885uwk"/><path class="af7iv3n-p"/><path class="x3jkjl77t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:umbrella-open-duotone-bold" /></template>
<style>
.af7iv3n-p {
  d: path("M12 2v2.5");
}

.evq885uwk {
  d: path("m5 3 2 2");
}

.gk4de-b1j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hyp6v68rm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ko52u6bwb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l10is9spu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 3 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qxhe48bjs {
  d: path("M12 14v7");
}

.ra0ia6tpa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 3 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v2mer508z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 14v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wwozeg7ww {
  d: path("M3 14a9 9 0 0 1 18 0");
}

.x3jkjl77t {
  d: path("m19 3 -2 2");
}

.yih0nfb7c {
  d: path("M3 14h18");
}

</style>
