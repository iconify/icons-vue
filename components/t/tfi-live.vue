<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="o9m81bbpg"/><path class="qjqsp6bxh"/></g><ellipse class="cbet81bik"/><path class="q26xrbbtk"/><circle class="euvgedcmi"/><path class="jn9zwibjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tfi-live" /></template>
<style>
.cbet81bik {
  cx: 36.118px;
  cy: 35.032px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.382px;
  ry: 2.54px;
}

.euvgedcmi {
  cx: 13.92px;
  cy: 34.225px;
  r: 0.951px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jn9zwibjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.803 34.749c.628 2.624 3.11 4.505 3.11 4.505s2.544-1.867 3.11-4.505");
}

.o9m81bbpg {
  d: path("M5.5 5.843v10.789c.002 3.055 1.34 4.923 2.617 6.362s3.795 3.085 8.174 3.105h9.465v-9.465c-.02-4.38-1.666-6.898-3.104-8.174c-1.44-1.277-3.307-2.615-6.363-2.617zm16.338 6.275v9.253m-6.275-4.627h3.007");
}

.q26xrbbtk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.756 26.099l7.94 6.523m-1.649 4.45l-11.462 2.51m-6.671-8.565c-1.932 0-3.502 1.73-3.11 3.733c.185.946.668 1.865 1.237 2.612c-2.646.33-4.391 1.262-4.391 2.33c0 1.361 2.88 2.465 6.432 2.465c3.55 0 6.429-1.104 6.43-2.466c-.002-1.113-1.891-2.074-4.692-2.366c.56-.74 1.02-1.644 1.203-2.575c.392-2.004-1.178-3.733-3.11-3.733Z");
}

.qjqsp6bxh {
  d: path("M15.563 21.371v-9.253h4.627m-12.352 0h6.13m-3.065 9.253v-9.253");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
