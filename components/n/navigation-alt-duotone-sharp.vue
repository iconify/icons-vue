<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nb4dfqb0a"/><path class="d9q4v2bfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-alt-duotone-sharp" /></template>
<style>
.d9q4v2bfo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 12l3 9l-6-3l-6 3l6-18z");
}

.ft5dv1b6b {
  fill: none;
}

.nb4dfqb0a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m18 21l-6-3l-6 3l6-18Z");
}

</style>
