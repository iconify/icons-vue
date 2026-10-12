<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fsadfbyhn"/><path class="hneqsccfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wedding-chapel" /></template>
<style>
.fsadfbyhn {
  d: path("M12 5.5V2.75m-7.75 17.9V11.6q0-.6.49-.95l6.77-4.8q.49-.35.98 0l6.77 4.8q.49.35.49.95v9.05q0 .6-.6.6H4.85q-.6 0-.6-.6");
}

.hneqsccfn {
  d: path("m12 14.5l-2.1-2.05A1.3 1.3 0 0 1 12 10.9a1.3 1.3 0 0 1 2.1 1.55Zm-2 6.75v-2.5a2 2 0 0 1 4 0v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
