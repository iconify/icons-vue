<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="jqjpel2co"/><path class="j2n-gkmla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pulse-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j2n-gkmla {
  d: path("M240 128a8 8 0 0 1-8 8h-27.06l-37.78 75.58A8 8 0 0 1 160 216h-.4a8 8 0 0 1-7.08-5.14L95.35 60.76l-32.07 70.55A8 8 0 0 1 56 136H24a8 8 0 0 1 0-16h26.85l37.87-83.31a8 8 0 0 1 14.76.46l57.51 151l31.85-63.71A8 8 0 0 1 200 120h32a8 8 0 0 1 8 8");
}

.jqjpel2co {
  d: path("m96 40l33.52 88H56Zm104 88h-70.48L160 208Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
