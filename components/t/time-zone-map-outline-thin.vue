<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_ssmh9ez"/><path class="h2-2dgnfu"/><path class="fb4zxqney"/><path class="ln075ccaf"/><path class="cjzdtdb-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:time-zone-map-outline-thin" /></template>
<style>
.cjzdtdb-a {
  d: path("M16 15h2.5");
}

.fb4zxqney {
  d: path("M12 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.h2-2dgnfu {
  d: path("M12 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ln075ccaf {
  d: path("M16 12v3");
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

</style>
