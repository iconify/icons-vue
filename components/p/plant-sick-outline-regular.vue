<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n-0bvdyee"/><path class="vt7vyubju"/><path class="e49gfxbmn"/><path class="ip9t47bii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plant-sick-outline-regular" /></template>
<style>
.e49gfxbmn {
  d: path("M12 10c-4 0 -7 2 -7 5 4 0 7 -2 7 -5");
}

.ip9t47bii {
  d: path("M12 8c4 0 7 2 7 5 -4 0 -7 -2 -7 -5");
}

.n-0bvdyee {
  d: path("M9 15v5h6v-5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vt7vyubju {
  d: path("M12 4v11");
}

</style>
