<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_oqy2n_y"/><path class="xbjl58b2q"/><path class="dbly1fcej"/><path class="e77gki8ci"/><path class="y07a50u1t"/><path class="p0hi_9aen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:warehouse-shelf-duotone-regular" /></template>
<style>
.dbly1fcej {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 17h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e77gki8ci {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_oqy2n_y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 20V10l3 -3h14l3 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p0hi_9aen {
  d: path("M5 17h14");
}

.xbjl58b2q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y07a50u1t {
  d: path("M5 13h14");
}

</style>
