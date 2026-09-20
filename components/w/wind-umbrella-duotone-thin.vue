<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lpqu47bxv"/><path class="s9jzbjbwv"/><path class="iygpkbb2j"/><path class="w-bszmb4l"/><path class="bso0bbbqi"/><path class="vhnbtvbtn"/><path class="hiqcqfbaf"/><path class="yb0sj-xar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-umbrella-duotone-thin" /></template>
<style>
.bso0bbbqi {
  d: path("M21 8A9 9 0 0 1 3 8");
}

.hiqcqfbaf {
  d: path("M12 8v10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iygpkbb2j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lpqu47bxv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 8A9 9 0 0 1 3 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s9jzbjbwv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.w-bszmb4l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 18a2 2 0 0 1 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yb0sj-xar {
  d: path("M12 18a2 2 0 0 1 -4 0");
}

</style>
