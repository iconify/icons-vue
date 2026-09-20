<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGtMyKec6q"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="fay1j7b1r"/><path class="v-9f0t9_m"/><path class="vrtylbbea"/><path class="jodts7b6h"/></g></mask></defs><circle mask="url(#SVGtMyKec6q)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:sword-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.fay1j7b1r {
  d: path("M19.418 4.209a2 2 0 0 1 2.333 2.325l-.474 2.601a2 2 0 0 1-.551 1.053l-6.394 6.418a2 2 0 0 1-2.828.005l-2.126-2.117a2 2 0 0 1-.005-2.829l6.394-6.418a2 2 0 0 1 1.05-.554zm-.109 4.567l.475-2.601l-2.6.484l-6.394 6.418l2.125 2.117z");
}

.ft5dv1b6b {
  fill: none;
}

.jodts7b6h {
  d: path("M8.71 16.646L5.889 19.48l.708.706l2.823-2.834l1.417 1.412l-2.823 2.833a2 2 0 0 1-2.829.006l-.708-.706a2 2 0 0 1-.005-2.829l2.823-2.833z");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.v-9f0t9_m {
  d: path("M10.97 15.021a.75.75 0 0 1-.002-1.06l3.53-3.543a.75.75 0 1 1 1.062 1.059l-3.529 3.542a.75.75 0 0 1-1.06.002");
}

.vrtylbbea {
  d: path("M6.192 12.025a2.5 2.5 0 0 1 3.535-.007l4.25 4.235a2.5 2.5 0 1 1-3.528 3.542l-4.25-4.235a2.5 2.5 0 0 1-.007-3.535m2.124 1.41a.5.5 0 0 0-.706.708l4.25 4.235a.5.5 0 1 0 .706-.708z");
}

</style>
