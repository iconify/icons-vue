<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ii21ukrdd"/><path class="suuvw917c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-pin-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ii21ukrdd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 9H10a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1m-5 4h4v3l1 1c.369.369.369 1 0 1h-6c-.369 0-.369-.631 0-1l1-1Z");
}

.suuvw917c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 20H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v2m-5 5h4v3l1 1c.369.369.369 1 0 1h-6c-.369 0-.369-.631 0-1l1-1zm-1 0h6m-3 5v3");
}

</style>
