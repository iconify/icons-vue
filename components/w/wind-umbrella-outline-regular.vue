<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bso0bbbqi"/><path class="vhnbtvbtn"/><path class="hiqcqfbaf"/><path class="yb0sj-xar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-umbrella-outline-regular" /></template>
<style>
.bso0bbbqi {
  d: path("M21 8A9 9 0 0 1 3 8");
}

.hiqcqfbaf {
  d: path("M12 8v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.yb0sj-xar {
  d: path("M12 18a2 2 0 0 1 -4 0");
}

</style>
