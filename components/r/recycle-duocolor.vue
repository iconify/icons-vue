<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ec7g9wu4f"/><path class="pq61nfb5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:recycle-duocolor" /></template>
<style>
.ec7g9wu4f {
  stroke-opacity: 0.4;
  d: path("M7.795 17h-.5c-1.54 0-2.502-1.667-1.733-3L8.41 9.07m1.098 4.098L8.409 9.07L4.31 10.168");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pq61nfb5f {
  d: path("m10.509 5.433l.25-.433c.77-1.333 2.694-1.333 3.464 0l2.846 4.93M12.97 8.832l4.098 1.098l1.098-4.098m1.002 7.735l.25.433c.77 1.333-.193 3-1.732 3h-5.693m3-3l-3 3l3 3");
}

</style>
