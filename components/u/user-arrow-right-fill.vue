<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="wcyyvb42i"/><path class="lujihpb4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-arrow-right-fill" /></template>
<style>
.lujihpb4r {
  d: path("M16 6H22M19 3L22 6L19 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wcyyvb42i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 6C13 8.2091 11.2091 10 9 10C6.7909 10 5 8.2091 5 6C5 3.7909 6.7909 2 9 2C11.2091 2 13 3.7909 13 6ZM8 12L10 12C13.866 12 17 15.134 17 19V20C17 21.1046 16.1046 22 15 22L3 22C1.8954 22 1 21.1046 1 20V19C1 15.134 4.134 12 8 12Z");
  stroke: none;
}

</style>
