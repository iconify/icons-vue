<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oko5-fb7y"/><path class="nq59mtknl"/><path class="gt__-hbfh"/><path class="nca7pq6lm"/><path class="qcx0_7byx"/><path class="dwj8i8b7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:social-event-duotone-thin" /></template>
<style>
.dwj8i8b7i {
  d: path("M6 10c1 2 3 2 4 0 1 2 3 2 4 0 1 2 3 2 4 0");
}

.gt__-hbfh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10c1 2 3 2 4 0 1 2 3 2 4 0 1 2 3 2 4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nca7pq6lm {
  d: path("m4 10 8 -8 8 8");
}

.nq59mtknl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10v10h12V10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oko5-fb7y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 10 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qcx0_7byx {
  d: path("M6 10v10h12V10");
}

</style>
