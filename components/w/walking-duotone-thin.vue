<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oe3oa5b3b"/><path class="w08657bnd"/><path class="owfn5sxxm"/><path class="tk9hd5usx"/><path class="mdw7p8b6l"/><path class="cy0m90bbz"/><path class="ggxa63i9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:walking-duotone-thin" /></template>
<style>
.cy0m90bbz {
  d: path("M8 18H5");
}

.ggxa63i9q {
  d: path("M16 18h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mdw7p8b6l {
  d: path("m8 18 4 -4 4 4");
}

.oe3oa5b3b {
  fill: currentColor;
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.owfn5sxxm {
  d: path("M12 8v6");
}

.tk9hd5usx {
  d: path("m9 13 3 -3 3 3");
}

.w08657bnd {
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
