<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sn70fibvm"/><path class="oc256ggcz"/><path class="p5qqdijym"/><path class="xnvv0pb9e"/><path class="qoc2w7prb"/><path class="baqv_u95v"/><path class="xnwp-xx6w"/><path class="xmvb6bcje"/><path class="jg4jvf8pr"/><path class="e69g47h7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-selection-broken" /></template>
<style>
.baqv_u95v {
  d: path("M22 20C22 21.1046 21.1046 22 20 22C18.8954 22 18 21.1046 18 20C18 18.8954 18.8954 18 20 18C21.1046 18 22 18.8954 22 20Z");
}

.e69g47h7j {
  d: path("M4 6V18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg4jvf8pr {
  d: path("M18 20L12 20M8 20L6 20");
}

.oc256ggcz {
  d: path("M12 15L12 9");
}

.p5qqdijym {
  d: path("M6 4C6 5.10457 5.10457 6 4 6C2.89543 6 2 5.10457 2 4C2 2.89543 2.89543 2 4 2C5.10457 2 6 2.89543 6 4Z");
}

.qoc2w7prb {
  d: path("M22 4C22 5.10457 21.1046 6 20 6C18.8954 6 18 5.10457 18 4C18 2.89543 18.8954 2 20 2C21.1046 2 22 2.89543 22 4Z");
}

.sn70fibvm {
  d: path("M9 9H15");
}

.xmvb6bcje {
  d: path("M20 18V12M20 8V6");
}

.xnvv0pb9e {
  d: path("M6 20C6 21.1046 5.10457 22 4 22C2.89543 22 2 21.1046 2 20C2 18.8954 2.89543 18 4 18C5.10457 18 6 18.8954 6 20Z");
}

.xnwp-xx6w {
  d: path("M18 4H6");
}

</style>
