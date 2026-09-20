<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u9-qnozzt"/><path class="y7f50bciz"/><path class="qir7x_1xu"/><path class="lq7nhzb8r"/><path class="qgq3udbvd"/><path class="xf07dvr8m"/><path class="tr_jskylo"/><path class="hxoe7gx5p"/><path class="e0001wg8c"/><path class="y_21nobec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:waterfall-duotone-thin" /></template>
<style>
.e0001wg8c {
  d: path("M17 5v12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxoe7gx5p {
  d: path("M12 5v12");
}

.lq7nhzb8r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qgq3udbvd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 21 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qir7x_1xu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tr_jskylo {
  d: path("M7 5v12");
}

.u9-qnozzt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xf07dvr8m {
  d: path("M2 5h20");
}

.y_21nobec {
  d: path("m3 21 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

.y7f50bciz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
