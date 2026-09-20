<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uverd3z0e"/><path class="k3x4ygb5y"/><path class="r_je2bdjk"/><path class="xyf3o9drf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reflection-outline-regular" /></template>
<style>
.k3x4ygb5y {
  d: path("M15.5 5.94a7 7 0 0 1 0 12.12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r_je2bdjk {
  d: path("M12 4v5");
}

.uverd3z0e {
  d: path("M8.5 18.06a7 7 0 0 1 0 -12.12");
}

.xyf3o9drf {
  d: path("M12 15v5");
}

</style>
