<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ujm4ls9cq"/><path class="daxgvdb-d"/><path class="fl8ls8bxt"/><path class="rzz6z1b-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:orangutan-sharp" /></template>
<style>
.daxgvdb-d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 10c0-1.5 1.5-2.75 3.75-2.75S15.75 8.5 15.75 10v3.5C15.75 16.25 14 18 12 18s-3.75-1.75-3.75-4.5ZM4.5 16L4 18.5M19.5 16l.5 2.5");
}

.fl8ls8bxt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 10.75h.01m2.99 0h.01");
}

.rzz6z1b-j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.5 15.25l1.5.9l1.5-.9");
}

.ujm4ls9cq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5c3 0 5 1.75 5.25 4.5l2.5.5l1.5.375v6.775L19.5 16l-2 .25C17.25 19 15 21 12 21s-5.25-2-5.5-4.75l-2-.25l-1.75-.35V8.875l1.5-.375l2.5-.5C7 5.25 9 3.5 12 3.5Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
