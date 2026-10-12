<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dg67scbsc"/><circle class="sapxmnb0l"/><path class="sl2rqs8ez"/><path class="v8nz8xqan"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pliers" /></template>
<style>
.dg67scbsc {
  d: path("M9.75 8.5V4.75c0-1.25 1-2 2.25-2s2.25.75 2.25 2V8.5Zm2.25-4v2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sapxmnb0l {
  cx: 12px;
  cy: 10.5px;
  r: 2px;
}

.sl2rqs8ez {
  d: path("m10.91 13.16l.43.18q.91.41.46 1.3l-2.85 5.72q-.45.89-1.39.55l-.87-.32q-.94-.34-.45-1.21l3.27-5.76q.49-.87 1.4-.46");
}

.v8nz8xqan {
  d: path("m14.49 13.62l3.27 5.76q.49.87-.45 1.21l-.87.32q-.94.34-1.39-.55l-2.85-5.72q-.45-.89.46-1.3l.43-.18q.91-.41 1.4.46");
}

</style>
