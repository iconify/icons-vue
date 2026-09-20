<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iitrn5u7g"/><path class="yq08e12ht"/><path class="k7zxbznhw"/><path class="oatswtbtv"/><path class="hsnj9o-9y"/><path class="bgz3owcvd"/><path class="vux4gkbhn"/><path class="nj9g-accq"/><path class="axyqg5uel"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stacked-bar-duotone-thin" /></template>
<style>
.axyqg5uel {
  d: path("M16 14v6");
}

.bgz3owcvd {
  d: path("M8 4v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hsnj9o-9y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iitrn5u7g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkuojibnm {
  d: path("M3 20h18");
}

.k7zxbznhw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nj9g-accq {
  d: path("M16 8v3");
}

.oatswtbtv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vux4gkbhn {
  d: path("M8 14v6");
}

.yq08e12ht {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
