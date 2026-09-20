<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yejxb6b5w"/><path class="obeew47lh"/><path class="yrana5b4o"/><path class="l8umwjbkw"/><path class="ymhw07_9a"/><path class="wlpa9-b1f"/><path class="aut8y9hmn"/><path class="k6x6uv-ap"/><path class="h2va4xb2x"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:museum-duotone-thin" /></template>
<style>
.aut8y9hmn {
  d: path("M7 12v7");
}

.bos0j4biy {
  d: path("M3 21h18");
}

.h2va4xb2x {
  d: path("M17 11v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6x6uv-ap {
  d: path("M12 11v8");
}

.l8umwjbkw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.obeew47lh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wlpa9-b1f {
  d: path("m5 11 7 -7 7 7");
}

.yejxb6b5w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 11 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymhw07_9a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yrana5b4o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
