<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j835zw5-z"/><path class="xyj-l9cjp"/><path class="k7ro6rbzz"/><path class="dgfbh6b4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mesh-gen-outline-thin" /></template>
<style>
.dgfbh6b4z {
  d: path("M12 9v9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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
