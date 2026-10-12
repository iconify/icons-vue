<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sdixdac4z"/><path class="rraudlb7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sand-castle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rraudlb7w {
  d: path("M10.75 21v-2.25a1.25 1.25 0 0 1 2.5 0V21M12 8.5V5.75m.37-2.86l3.26 1.22q.37.14 0 .28l-3.26 1.22q-.37.14-.37-.26v-2.2q0-.4.37-.26");
}

.sdixdac4z {
  d: path("M3.6 21h16.8q.35 0 .35-.35v-6.3q0-.35-.35-.35h-1.05q-.35 0-.35.35v.8q0 .35-.35.35h-.8q-.35 0-.35-.35v-.8q0-.35-.35-.35h-1.8q-.35 0-.35-.35v-4.8q0-.35-.35-.35h-.55q-.35 0-.35.35v.8q0 .35-.35.35h-.45q-.35 0-.35-.35v-.8q0-.35-.35-.35h-.5q-.35 0-.35.35v.8q0 .35-.35.35h-.45q-.35 0-.35-.35v-.8q0-.35-.35-.35h-.55Q9 8.5 9 8.85v4.8q0 .35-.35.35h-1.8q-.35 0-.35.35v.8q0 .35-.35.35h-.8q-.35 0-.35-.35v-.8Q5 14 4.65 14H3.6q-.35 0-.35.35v6.3q0 .35.35.35");
}

</style>
