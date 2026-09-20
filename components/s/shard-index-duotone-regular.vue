<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ow9nvovdw"/><path class="o0rovcb6f"/><path class="wxx-lxpns"/><path class="nd5hszblz"/><path class="vra4pq0jr"/><path class="xw66a0v9s"/><path class="b7nacdcee"/><path class="f8c172gmh"/><path class="qnmmmsbha"/><path class="zhf4ld96p"/><path class="tk_gkbbsy"/><path class="czv374byt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shard-index-duotone-regular" /></template>
<style>
.b7nacdcee {
  d: path("M3 6h6");
}

.czv374byt {
  d: path("M10 16h11");
}

.f8c172gmh {
  d: path("M12 6h9");
}

.nd5hszblz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o0rovcb6f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ow9nvovdw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qnmmmsbha {
  d: path("M3 11h11");
}

.tk_gkbbsy {
  d: path("M3 16h4");
}

.vra4pq0jr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wxx-lxpns {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xw66a0v9s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zhf4ld96p {
  d: path("M17 11h4");
}

</style>
