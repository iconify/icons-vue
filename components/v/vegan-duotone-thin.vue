<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sknn5dbsy"/><path class="j7h3npb4b"/><path class="p-4c_po-t"/><path class="w89kumbyo"/><path class="mho7bk0jd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vegan-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7h3npb4b {
  fill: currentColor;
  d: path("M12 13c0 -5 4 -8 9 -8 0 5 -4 8 -9 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mho7bk0jd {
  d: path("M12 13c0 -5 4 -8 9 -8 0 5 -4 8 -9 8");
}

.p-4c_po-t {
  d: path("M12 21v-8");
}

.sknn5dbsy {
  fill: currentColor;
  d: path("M12 13c0 -5 -4 -8 -9 -8 0 5 4 8 9 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w89kumbyo {
  d: path("M12 13c0 -5 -4 -8 -9 -8 0 5 4 8 9 8");
}

</style>
