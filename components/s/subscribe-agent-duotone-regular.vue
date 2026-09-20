<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jlxwz7w4c"/><path class="kosxb-loy"/><path class="i_m6df3yl"/><path class="j_ile9bol"/><path class="skbifdbcx"/><path class="mk37pkb8m"/><path class="xupj3fbjb"/><path class="k5yx_gble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:subscribe-agent-duotone-regular" /></template>
<style>
.i_m6df3yl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 15a3 3 0 0 1 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j_ile9bol {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12a6 6 0 0 1 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jlxwz7w4c {
  fill: currentColor;
  d: path("M12 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k5yx_gble {
  d: path("M12 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kosxb-loy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mk37pkb8m {
  d: path("M13 15a3 3 0 0 1 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.xupj3fbjb {
  d: path("M13 12a6 6 0 0 1 6 6");
}

</style>
