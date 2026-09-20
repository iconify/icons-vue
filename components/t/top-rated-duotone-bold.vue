<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hmkpulkfg"/><path class="qc4wqxber"/><path class="odr8rqgtj"/><path class="adxensbci"/><path class="aindk3bza"/><path class="h8-owobfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:top-rated-duotone-bold" /></template>
<style>
.adxensbci {
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
}

.aindk3bza {
  d: path("M12 5.5v6");
}

.h8-owobfd {
  d: path("m10 7.5 2 -2");
}

.hmkpulkfg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2a6.5 6.5 0 1 1 0 13 6.5 6.5 0 1 1 0 -13M9.5 14.5V22l2.5 -2.5 2.5 2.5v-7.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.odr8rqgtj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 7.5 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qc4wqxber {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 5.5v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
