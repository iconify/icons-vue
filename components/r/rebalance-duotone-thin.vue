<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o6hvby18z"/><path class="m8zldf86r"/><path class="qsz0lkb9n"/><path class="mokr9feot"/><path class="p6ki6eqhw"/><path class="x4q3oe16k"/><path class="x5li7lwaz"/><path class="jwnes9bsk"/><path class="evty0vb8w"/><path class="nijl6gb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rebalance-duotone-thin" /></template>
<style>
.evty0vb8w {
  d: path("M5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwnes9bsk {
  d: path("M8 19h8");
}

.m8zldf86r {
  fill: currentColor;
  d: path("M17 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mokr9feot {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nijl6gb2v {
  d: path("M17 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.o6hvby18z {
  fill: currentColor;
  d: path("M5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p6ki6eqhw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qsz0lkb9n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h18M3 7a3 3 0 0 0 6 0m6 0a3 3 0 0 0 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x4q3oe16k {
  d: path("M3 7h18M3 7a3 3 0 0 0 6 0m6 0a3 3 0 0 0 6 0");
}

.x5li7lwaz {
  d: path("M12 7v12");
}

</style>
