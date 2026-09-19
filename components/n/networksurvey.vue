<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hfyoefbvp"/><path class="ygxpln14i"/><path class="yph44ccvj"/><ellipse transform="rotate(-48.828 11.78 15.277)" class="ulsxu47hv"/><path class="q4vdbobei"/><path class="j-2-u0btv"/><path class="ybjftub2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:networksurvey" /></template>
<style>
.hfyoefbvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.056 7.182v29.843m12.581-24.747v29.843M42.5 35.722L30.637 42.12l-12.58-5.096L5.5 41.335V11.492l12.556-4.31l12.58 5.095L42.5 5.88Z");
}

.j-2-u0btv {
  fill: none;
  stroke: currentColor;
  d: path("m9.614 26.35l4.27-1.719m-3.537-.759l2.58-1.038");
}

.q4vdbobei {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 3 3;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 35.81s2.066-11.213 15.58-7.696c15.612 4.062 13.876-8.495 13.25-12.767");
}

.ulsxu47hv {
  cx: 11.779px;
  cy: 15.277px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.828px;
  ry: 0.633px;
}

.ybjftub2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.04 18.385a2.29 2.29 0 0 1-1.596-2.324a4.38 4.38 0 0 1 1.596-3.203m3.24 4.634a4.38 4.38 0 0 0 1.595-3.203a2.29 2.29 0 0 0-1.595-2.323");
}

.ygxpln14i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.677 28.775s3.103-9.466 3.103-13.531");
}

.yph44ccvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.707 26.366a26 26 0 0 1-2.928-11.121");
}

</style>
