<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="epwe3rblo"/><path class="hf_gtezns"/><path class="ilenwpbkm"/><path class="h-8pk037m"/><path class="j835zw5-z"/><path class="xyj-l9cjp"/><path class="k7ro6rbzz"/><path class="dgfbh6b4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mesh-gen-duotone-thin" /></template>
<style>
.dgfbh6b4z {
  d: path("M12 9v9");
}

.epwe3rblo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h-8pk037m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hf_gtezns {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ilenwpbkm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 18 9 -9 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j835zw5-z {
  d: path("M3 9h18");
}

.k7ro6rbzz {
  d: path("m3 18 9 -9 9 9");
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
