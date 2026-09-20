<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kt4jgwb2r"/><path class="j-70hcbzd"/><path class="j_72l_3ug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:test-shard-outline-regular" /></template>
<style>
.j_72l_3ug {
  d: path("m17 8 4 4 -4 4Z");
}

.j-70hcbzd {
  d: path("m10 8 4 4 -4 4Z");
}

.kt4jgwb2r {
  d: path("m3 8 4 4 -4 4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
