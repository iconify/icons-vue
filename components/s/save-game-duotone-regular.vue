<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xu3q-b_rm"/><path class="eq8p65fcb"/><path class="itwbxpr-a"/><path class="kct9dt-jd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:save-game-duotone-regular" /></template>
<style>
.eq8p65fcb {
  d: path("M4 4v16h16V4Z");
}

.itwbxpr-a {
  d: path("M8 4v5h8V4");
}

.kct9dt-jd {
  d: path("M8 20v-6h8v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xu3q-b_rm {
  fill: currentColor;
  d: path("M4 4v16h16V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
