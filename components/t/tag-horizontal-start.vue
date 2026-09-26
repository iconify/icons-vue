<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vmvu4abgj"/><path class="mabku0myx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-start" /></template>
<style>
.mabku0myx {
  fill: currentColor;
  d: path("M10.5 12C10.5 12.8284 9.8284 13.5 9 13.5C8.1716 13.5 7.5 12.8284 7.5 12C7.5 11.1716 8.1716 10.5 9 10.5C9.8284 10.5 10.5 11.1716 10.5 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vmvu4abgj {
  d: path("M19 4L10 4C9.469567 4 8.96086 4.210712 8.585786 4.585786L2.585786 10.585786C1.804693 11.366879 1.804693 12.633121 2.585786 13.414214L8.585786 19.414214C8.96086 19.789288 9.469567 20 10 20L19 20C20.656854 20 22 18.656854 22 17L22 7C22 5.343146 20.656854 4 19 4Z");
}

</style>
