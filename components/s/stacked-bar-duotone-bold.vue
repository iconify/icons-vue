<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="py6kisbqn"/><path class="cdyi--bfo"/><path class="r51b5du2m"/><path class="gujfy_b4w"/><path class="hpm6v1-ys"/><path class="bgz3owcvd"/><path class="vux4gkbhn"/><path class="nj9g-accq"/><path class="axyqg5uel"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stacked-bar-duotone-bold" /></template>
<style>
.axyqg5uel {
  d: path("M16 14v6");
}

.bgz3owcvd {
  d: path("M8 4v7");
}

.cdyi--bfo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gujfy_b4w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hpm6v1-ys {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.nj9g-accq {
  d: path("M16 8v3");
}

.py6kisbqn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r51b5du2m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vux4gkbhn {
  d: path("M8 14v6");
}

</style>
