<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h6v5h0bhu"/><circle class="fnx3no86t"/><path class="qnfmfdc7y"/><rect class="j3s9ivbxi"/><path class="tty1brbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:numpuz" /></template>
<style>
.fnx3no86t {
  cx: 36.285px;
  cy: 25.058px;
  r: 2.076px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h6v5h0bhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.144 9.29l1.567-.853v6.266m.504 12.43v-6.266l-3.363 4.209h4.151m-3.371 14.425l3.371-6.267H9.852");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.qnfmfdc7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.177 21.631c-.346-.453-.873-.764-1.746-.764h-.146c-1.146 0-2.075.93-2.075 2.076v2.114M21.924 10.512a2.078 2.078 0 0 1 4.14-.233c.065.656-.143 1.303-.596 1.701c-.84.737-3.544 2.723-3.544 2.723h4.152m8.33-.529c.433.363.9.529 1.948.529h.245a1.566 1.566 0 0 0 0-3.132M34.405 8.96c.434-.361.901-.526 1.95-.524l.244.002a1.566 1.566 0 0 1 0 3.132m-1.204 0h1.204M23.49 36.368a1.567 1.567 0 0 0 0 3.133h1.02a1.567 1.567 0 0 0 0-3.133m0 0a1.567 1.567 0 0 0 0-3.133h-1.02a1.567 1.567 0 0 0 0 3.133m.001 0h1.018m-2.429-9.763c.434.362.853.528 1.902.528h.18a1.757 1.757 0 1 0 0-3.514h-2.081v-2.752h3.838");
}

.tty1brbkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 5.5v37m12.334-37v37M42.5 17.833h-37m37 12.334h-37");
}

</style>
