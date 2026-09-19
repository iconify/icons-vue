<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ogoquzbqn"/><path class="gij_zsb6o"/><path class="usdfooyrl"/><path class="teu-1ious"/><path class="g06o4rb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:patrika-news" /></template>
<style>
.g06o4rb3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24m43 0c0-11.874-9.626-21.5-21.5-21.5S2.5 12.126 2.5 24");
}

.gij_zsb6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.193 2.859C36.445 15.73 40.898 29.586 36.93 41.09");
}

.ogoquzbqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.97 40.99c12.055-7.753 21.275-22.442 21.008-36.831");
}

.teu-1ious {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.317 19.932c14.906 15.022 25.81 17.157 39.515 14.039");
}

.usdfooyrl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.984 25.867c9.853-15.039 23.792-18.19 38.564-13.788");
}

</style>
