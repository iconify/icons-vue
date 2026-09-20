<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zxrob3sge"/><path class="cpc3z_b1u"/><path class="jvexbw_pg"/><path class="axrx-_boy"/><path class="dfcdzc65k"/><path class="yg66nzbgg"/><path class="avkaqpora"/><path class="kdmnrabtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-connection-duotone-regular" /></template>
<style>
.avkaqpora {
  d: path("m13.5 13.5 2 2");
}

.axrx-_boy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13.5 13.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cpc3z_b1u {
  fill: currentColor;
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dfcdzc65k {
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.jvexbw_pg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8.5 8.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kdmnrabtq {
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yg66nzbgg {
  d: path("m8.5 8.5 2 2");
}

.zxrob3sge {
  fill: currentColor;
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
