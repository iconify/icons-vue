<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p5qqdijym"/><path class="xnvv0pb9e"/><path class="uqdxll9yb"/><path class="nborjbb0w"/><path class="qoc2w7prb"/><path class="e69g47h7j"/><path class="l7bia5acn"/><path class="nd8xspblj"/><path class="jpukyobyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transmission-linear" /></template>
<style>
.e69g47h7j {
  d: path("M4 6V18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpukyobyo {
  stroke-linejoin: round;
  d: path("M19.8571 18.5H20.2857C21.2325 18.5 22 17.7165 22 16.75C22 15.7835 21.2325 15 20.2857 15H18V18.5M19.8571 18.5H18M19.8571 18.5L22 22M18 18.5V22");
}

.l7bia5acn {
  d: path("M12 6V18");
}

.nborjbb0w {
  d: path("M14 4C14 5.10457 13.1046 6 12 6C10.8954 6 10 5.10457 10 4C10 2.89543 10.8954 2 12 2C13.1046 2 14 2.89543 14 4Z");
}

.nd8xspblj {
  d: path("M20 6V8C20 9.88562 20 10.8284 19.4142 11.4142C18.8284 12 17.8856 12 16 12H4");
}

.p5qqdijym {
  d: path("M6 4C6 5.10457 5.10457 6 4 6C2.89543 6 2 5.10457 2 4C2 2.89543 2.89543 2 4 2C5.10457 2 6 2.89543 6 4Z");
}

.qoc2w7prb {
  d: path("M22 4C22 5.10457 21.1046 6 20 6C18.8954 6 18 5.10457 18 4C18 2.89543 18.8954 2 20 2C21.1046 2 22 2.89543 22 4Z");
}

.uqdxll9yb {
  d: path("M14 20C14 21.1046 13.1046 22 12 22C10.8954 22 10 21.1046 10 20C10 18.8954 10.8954 18 12 18C13.1046 18 14 18.8954 14 20Z");
}

.xnvv0pb9e {
  d: path("M6 20C6 21.1046 5.10457 22 4 22C2.89543 22 2 21.1046 2 20C2 18.8954 2.89543 18 4 18C5.10457 18 6 18.8954 6 20Z");
}

</style>
