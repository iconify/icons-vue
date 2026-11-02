<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b16_kugxl"/><path class="m7w5vhb4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-duotone-round" /></template>
<style>
.b16_kugxl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16.071 10.343l.799 4.795a2.3 2.3 0 0 1-.081 1.115c-.262.816-.937 1.486-1.837 1.423a1.6 1.6 0 0 1-1.176-.642l-2.075-2.766l-.701.35v.675c0 1.119-.768 2.414-2 2.414c-.453 0-.887-.18-1.207-.5l-3-3c-.32-.32-.5-.754-.5-1.207c0-1.232 1.295-2 2.414-2h.675l.35-.701l-2.766-2.075a1.6 1.6 0 0 1-.642-1.176c-.063-.9.607-1.575 1.423-1.837a2.3 2.3 0 0 1 1.115-.081l4.795.799l1.636-1.636c.77-.771 1.784-1.678 2.886-1.899c.99-.197 1.836.207 2.528.899c1.951 1.952.536 3.878-1 5.414Z");
}

.ft5dv1b6b {
  fill: none;
}

.m7w5vhb4k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 8l-2 2l.884 5.303c.073.437-.07.883-.384 1.197a.613.613 0 0 1-.924-.066L12 13l-2 1v1.293c0 .453-.18.887-.5 1.207a.707.707 0 0 1-1 0l-3-3a.707.707 0 0 1 0-1c.32-.32.754-.5 1.207-.5H8l1-2l-3.434-2.576A.613.613 0 0 1 5.5 6.5c.314-.314.76-.457 1.197-.384L12 7l2-2c2-2 3-2 4-1s1 2-1 4M3 21h18");
}

</style>
