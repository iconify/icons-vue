<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ak-drqc-a"/><path class="vmvu4abgj"/><path class="mabku0myx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-start-two-tone" /></template>
<style>
.ak-drqc-a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 3C21.209139 3 23 4.790861 23 7L23 17C23 19.209139 21.209139 21 19 21L10 21C9.20435 21 8.441289 20.683929 7.87868 20.12132L1.87868 14.12132C0.707107 12.949747 0.707107 11.050253 1.87868 9.87868L7.87868 3.87868C8.441289 3.316071 9.20435 3 10 3L19 3Z");
  stroke: none;
}

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
