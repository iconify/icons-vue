<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ddplxgx2s"/><path class="qg4ud0b0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-start-percent" /></template>
<style>
.ddplxgx2s {
  d: path("M19 4L10 4C9.469567 4 8.96086 4.210712 8.585786 4.585786L2.585786 10.585786C1.804693 11.366879 1.804693 12.633121 2.585786 13.414214L8.585786 19.414214C8.96086 19.789288 9.469567 20 10 20L19 20C20.656854 20 22 18.656854 22 17L22 7C22 5.343146 20.656854 4 19 4ZM11.25 15L17.25 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qg4ud0b0f {
  fill: currentColor;
  d: path("M12.75 8.5C12.75 9.3284 12.0784 10 11.25 10C10.4216 10 9.75 9.3284 9.75 8.5C9.75 7.6716 10.4216 7 11.25 7C12.0784 7 12.75 7.6716 12.75 8.5ZM18.75 15.5C18.75 16.3284 18.0784 17 17.25 17C16.4216 17 15.75 16.3284 15.75 15.5C15.75 14.6716 16.4216 14 17.25 14C18.0784 14 18.75 14.6716 18.75 15.5Z");
  stroke: none;
}

</style>
