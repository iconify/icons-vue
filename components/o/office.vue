<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dvctv5bws"/><path class="mv7tuk22p"/><rect class="kgugjubnt"/><rect class="qnuw40b6v"/><path class="vgikbsb2x"/><rect class="c8zoaebdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:office" /></template>
<style>
.c8zoaebdv {
  width: 17.295px;
  height: 17.295px;
  x: 5.5px;
  y: 25.205px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.dvctv5bws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.748 16.952v-5.609h.95a2.804 2.804 0 0 1 0 5.608zm-5.1-.011v-5.587h1.88a1.875 1.875 0 0 1 .001 3.75H7.65m10.199-3.738v5.586m0-2.793h1.826m-1.826-2.793h2.799");
}

.kgugjubnt {
  width: 17.295px;
  height: 17.295px;
  x: 25.205px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.mv7tuk22p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 7.229v13.566a2 2 0 0 0 2 2h13.295a2 2 0 0 0 2-2V7.5a2 2 0 0 0-2-2H7.229A1.73 1.73 0 0 0 5.5 7.23z");
}

.qnuw40b6v {
  width: 17.295px;
  height: 17.295px;
  x: 25.205px;
  y: 25.205px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.vgikbsb2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.742 18.471V8.959h3.2a3.2 3.2 0 0 1 0 6.39h-3.2m6.293 13.748l-3.183 4.756l3.183 4.756m-6.364-9.512l3.181 4.756l-3.181 4.756m-10.903-9.512l-2.81 9.511m-2.81-9.511l2.81 9.511m-2.81-9.511l-2.811 9.511m-2.81-9.511l2.81 9.511");
}

</style>
