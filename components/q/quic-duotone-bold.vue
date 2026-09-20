<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b0d8n0blp"/><path class="msje7gbcy"/><path class="kkvfu5bre"/><path class="dwze-roqx"/><path class="a78831x8h"/><path class="lg40ofb3n"/><path class="l517yxbln"/><path class="rzfubwb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quic-duotone-bold" /></template>
<style>
.a78831x8h {
  d: path("M2 5h6l4 4");
}

.b0d8n0blp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h6l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dwze-roqx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kkvfu5bre {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l517yxbln {
  d: path("M12 9v6");
}

.lg40ofb3n {
  d: path("M2 19h6l4 -4");
}

.msje7gbcy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h6l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rzfubwb2e {
  d: path("M12 12h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
