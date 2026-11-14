<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="clnd7jbpg"/><path class="fn64f81ms"/><path class="xpaw5r2wd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mental-health-clinic" /></template>
<style>
.clnd7jbpg {
  d: path("m4.456 8.712l5.875-4.838a2.625 2.625 0 0 1 3.338 0l5.875 4.838a2.63 2.63 0 0 1 .956 2.027v7.636A2.625 2.625 0 0 1 17.875 21H6.125A2.625 2.625 0 0 1 3.5 18.375v-7.636a2.63 2.63 0 0 1 .956-2.027");
}

.fn64f81ms {
  d: path("M12 9.5C11.5 8 8.5 8 8.5 10c-2 0-2.5 2.5-1.5 3.5c-1 1.5 0 3 1.5 3h7c1.5 0 2.5-1.5 1.5-3c1-1 .5-3.5-1.5-3.5c0-2-3-2-3.5-.5m0 0v8.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpaw5r2wd {
  d: path("M7 13.5c1.5 0 2.25-.75 2.25-1.5M17 13.5c-1.5 0-2.25-.75-2.25-1.5");
}

</style>
