<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gw5inactd"/><path class="prboy499u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:snowflake-duocolor-round" /></template>
<style>
.gw5inactd {
  stroke-opacity: 0.4;
  d: path("m12 7.5l-2-2m2 2l2-2m1.897 4.25l.732-2.732m-.732 2.732l2.732.732m-2.732 3.768l2.732-.732m-2.732.732l.732 2.732M12 16.5l2 2m-2-2l-2 2m-1.897-4.25l-.732 2.732m.732-2.732l-2.732-.732M8.103 9.75l-2.732.732m2.732-.732L7.37 7.018");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.prboy499u {
  d: path("M12 12V3m0 9l7.794-4.5M12 12l7.794 4.5M12 12v9m0-9l-7.794 4.5M12 12L4.206 7.5");
}

</style>
