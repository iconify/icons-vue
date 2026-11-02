<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xsygsj3iv"/><path class="z90hmcu9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:twitch-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xsygsj3iv {
  stroke-opacity: 0.4;
  d: path("M4 3h16v10l-4 4h-4l-4 4v-4H4Z");
}

.z90hmcu9i {
  d: path("M12 7v4m4-4v4");
}

</style>
