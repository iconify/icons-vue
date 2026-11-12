<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tlxwtccin"/><path class="bo86ohb2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-user-duotone-sharp" /></template>
<style>
.bo86ohb2q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 9c2.667 1.111 2.667 4.889 0 6c1.219 2.552-1.448 5.219-4 4c-1.111 2.667-4.889 2.667-6 0c-2.552 1.219-5.219-1.448-4-4c-2.667-1.111-2.667-4.889 0-6c-1.219-2.552 1.448-5.219 4-4c1.111-2.667 4.889-2.667 6 0c2.552-1.219 5.219 1.448 4 4m-9 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M7 19a5 5 0 0 1 10 0");
}

.ft5dv1b6b {
  fill: none;
}

.tlxwtccin {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20.217 8.53c2.376 1.655 2.376 5.285 0 6.94c.617 2.786-1.961 5.364-4.747 4.747c-1.655 2.376-5.285 2.376-6.94 0c-2.786.617-5.364-1.961-4.747-4.747c-2.376-1.655-2.376-5.285 0-6.94c-.617-2.786 1.961-5.364 4.747-4.747c1.655-2.376 5.285-2.376 6.94 0c2.786-.617 5.364 1.961 4.747 4.747");
}

</style>
