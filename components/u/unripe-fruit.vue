<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ej5yr5ebw"/><path class="dqb1h-bkx"/><path class="jg9ddqonn"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:unripe-fruit" /></template>
<style>
.dqb1h-bkx {
  d: path("M11.75 8q0-3 1.5-5.5");
}

.ej5yr5ebw {
  d: path("M19.736 11.977C19.424 6.472 14.175 6.06 11.75 8c-2.5-2-8-1.5-8 4.5c0 4.5 3 8 5.5 8c1 0 1.75-.5 2.5-.5c.321 0 .642.092.982.196");
}

.jg9ddqonn {
  d: path("M12.75 4q2.5-2.25 5.5-1q-2.5 2.5-5.5 1Zm2.75 10.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
