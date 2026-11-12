<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x28oh5b4s"/><path class="myxug-jfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-foldable-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.myxug-jfn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 5l7-2h4l7 2v14l-7 2h-4l-7-2zm3 2h.01M12 3v18");
}

.x28oh5b4s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.725 2.038Q9.86 2 10 2h4q.14 0 .275.038l7 2c.429.123.725.516.725.962v14c0 .446-.296.839-.725.962l-7 2Q14.14 22 14 22h-4q-.14 0-.275-.038l-7-2A1 1 0 0 1 2 19V5c0-.446.296-.839.725-.962Z");
}

</style>
