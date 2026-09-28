<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jme_vab7f"/><path class="afjmqabbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tennis-ball-duotone" /></template>
<style>
.afjmqabbu {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12Z");
}

.jme_vab7f {
  stroke-opacity: 0.4;
  d: path("M12 2C12.2348 2.7627 12.3542 3.5562 12.3542 4.3542C12.3542 8.7725 8.7725 12.3542 4.3542 12.3542C3.5562 12.3542 2.7627 12.2348 2 12M12 22C11.7652 21.2373 11.6458 20.4438 11.6458 19.6458C11.6458 15.2275 15.2275 11.6458 19.6458 11.6458C20.4438 11.6458 21.2373 11.7652 22 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
