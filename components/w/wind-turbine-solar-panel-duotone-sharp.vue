<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mjcxu2bos"/><path class="t_9-itvsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wind-turbine-solar-panel-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mjcxu2bos {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m6.704 5.896l-.739-2.76c1.192.405 1.562 1.747 1.605 2.877Zm-.512 1.912l-2.02 2.02C3.926 8.594 4.904 7.602 5.861 7Zm1.912-.512l2.76.739c-.946.831-2.294.479-3.294-.048ZM11 21l1-8h8l1 8Z");
}

.t_9-itvsu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 1v13m4 0l1-8h8l1 8ZM8.104 7.296l2.76.74c-.774.68-1.952.66-3.294-.05Zm-1.912.512l-2.02 2.02C3.97 8.818 4.576 7.808 5.86 7Zm.512-1.912l-.74-2.76c.977.33 1.548 1.36 1.606 2.877ZM16 13v8m-4.5-4h9");
}

</style>
