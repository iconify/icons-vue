<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g clip-rule="evenodd" class="d2kvgvbvc"><path class="ozahkvgqs"/><path class="p3mf-k4nc"/><path class="u2oj9bcez"/><path class="dr572bckh"/></g><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:sword-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dr572bckh {
  d: path("M5.71 13.646L2.889 16.48l.708.706l2.823-2.834l1.417 1.412l-2.823 2.833a2 2 0 0 1-2.829.006l-.708-.706a2 2 0 0 1-.005-2.829l2.823-2.833z");
}

.ozahkvgqs {
  d: path("M16.418 1.209a2 2 0 0 1 2.333 2.325l-.474 2.601a2 2 0 0 1-.551 1.053l-6.394 6.418a2 2 0 0 1-2.828.005l-2.126-2.117a2 2 0 0 1-.005-2.829l6.394-6.418a2 2 0 0 1 1.05-.554zm-.109 4.567l.475-2.601l-2.6.484l-6.394 6.418l2.125 2.117z");
}

.p3mf-k4nc {
  d: path("M7.97 12.021a.75.75 0 0 1-.002-1.06l3.53-3.543a.75.75 0 1 1 1.062 1.059l-3.529 3.542a.75.75 0 0 1-1.06.002");
}

.u2oj9bcez {
  d: path("M3.192 9.025a2.5 2.5 0 0 1 3.535-.007l4.25 4.235a2.5 2.5 0 1 1-3.528 3.542l-4.25-4.235a2.5 2.5 0 0 1-.007-3.535m2.124 1.41a.5.5 0 0 0-.706.708l4.25 4.235a.5.5 0 1 0 .706-.708z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
