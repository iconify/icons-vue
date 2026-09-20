<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tt88ss5fm"/><path class="wrdzdhojp"/><path class="vl47r8b0v"/><path class="v679oactm"/><path class="l074bgbxo"/><path class="hh5ontkjw"/><path class="wwozeg7ww"/><path class="yih0nfb7c"/><path class="qxhe48bjs"/><path class="evq885uwk"/><path class="af7iv3n-p"/><path class="x3jkjl77t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:umbrella-open-duotone-thin" /></template>
<style>
.af7iv3n-p {
  d: path("M12 2v2.5");
}

.evq885uwk {
  d: path("m5 3 2 2");
}

.hh5ontkjw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 3 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l074bgbxo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 2v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qxhe48bjs {
  d: path("M12 14v7");
}

.tt88ss5fm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 14a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v679oactm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 3 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vl47r8b0v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 14v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wrdzdhojp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 14h18");
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
