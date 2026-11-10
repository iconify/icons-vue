<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r_es4dbra"/><path class="u4l6l8b8q"/><path class="rf84mq_ky"/><circle class="yl-d2qbiq"/><path class="ptdydnbbq"/><circle class="mcolj8btg"/><path class="linge7bll"/><ellipse class="g6zl2ox8o"/><path class="xd_4_4bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nearby-glasses" /></template>
<style>
.g6zl2ox8o {
  cx: 24px;
  cy: 29.91px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 14.464px;
  ry: 2.292px;
}

.linge7bll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.588 27.618v2.832");
}

.mcolj8btg {
  cx: 41.588px;
  cy: 26.202px;
  r: 1.416px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ptdydnbbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.25 26.48v2.831");
}

.r_es4dbra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.086 13.99c1.05 0 3.393.152 5.583 2.232c-1.314 2.409-.548 5.736-5.496 5.736s-4.729-4.882-4.729-6.37s3.635-1.599 4.642-1.599Z");
}

.rf84mq_ky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.77 15.978s.786-.8 1.312-.788l-.055-1.073c-1.894-.197-4.236-.043-4.236-.043M24 21.958v7.353");
}

.u4l6l8b8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.443 15.978s-.787-.8-1.313-.788l.055-1.073c1.894-.197 4.236-.043 4.236-.043m14.705-.084c-1.05 0-3.393.152-5.583 2.232c1.314 2.409.548 5.736 5.496 5.736s4.729-4.882 4.729-6.37s-3.635-1.599-4.642-1.599m-5.583 2.233s-.597-.076-.937-.076s-.937.076-.937.076");
}

.xd_4_4bib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.287 29.167c-1.77.48-2.787 1.045-2.787 1.647c0 1.766 8.73 3.197 19.5 3.197s19.5-1.431 19.5-3.197c0-.543-.827-1.055-2.287-1.503");
}

.yl-d2qbiq {
  cx: 12.25px;
  cy: 25.064px;
  r: 1.416px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
