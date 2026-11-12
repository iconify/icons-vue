<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g4c1tp6az"/><path class="mhlsn304v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-foldable-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g4c1tp6az {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M22 19c0 .446-.296.839-.725.962l-7 2Q14.14 22 14 22h-4q-.14 0-.275-.038l-7-2A1 1 0 0 1 2 19V5c0-.446.296-.839.725-.962l7-2Q9.86 2 10 2h4q.14 0 .275.038l7 2c.429.123.725.516.725.962Z");
}

.mhlsn304v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12v7l-7 2h-4l-7-2V5l7-2h4l7 2zM6 7h.01M12 3v18");
}

</style>
