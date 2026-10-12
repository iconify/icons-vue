<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="b1c5crw0p"/><path class="zefcpxxbh"/><path class="lcdu-hbje"/><path class="j5_oqbbme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:monkey-sharp" /></template>
<style>
.b1c5crw0p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.37 14.75a2.5 2.5 0 1 1 .18-4.98a7 7 0 0 1 12.9 0a2.5 2.5 0 1 1 .18 4.98a7 7 0 0 1-13.26 0Z");
}

.j5_oqbbme {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.5 14.25l1.5 1l1.5-1");
}

.lcdu-hbje {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10.75h.01m3.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zefcpxxbh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 9.25l-.75-.75h-3.5v3.083l.5.667l-.5.643v.857c0 1.75 1.9 3 4.25 3s4.25-1.25 4.25-3v-.857l-.5-.643l.5-.667V8.5h-3.5z");
}

</style>
