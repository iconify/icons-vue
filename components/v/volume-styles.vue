<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uek-bs_mh"/><circle class="nbog-pb-i"/><circle class="ficrw85uu"/><path class="j68vol3fw"/><circle class="r_qkoabbd"/><path class="j5nju7bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:volume-styles" /></template>
<style>
.ficrw85uu {
  cx: 34.5px;
  cy: 28px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j5nju7bbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.652 37.886c.21-.215.997-1.02 1.07-1.091c.163-.157.078-.409.078-.409s-.118-.51-.15-.853c-.025-.27-.31-.24-.31-.24h-1.15a.205.205 0 0 0-.183.19c-.078 1.038.506 2.15.623 2.363h0l.005.01za4.8 4.8 0 0 0 1.758 1.754l-.001.002l.06.034h0c.262.142 1.337.686 2.341.61c0 0 .163-.005.188-.183v-1.15s.03-.285-.24-.31c-.34-.033-.851-.15-.851-.15s-.251-.085-.408.078c-.07.073-.875.86-1.09 1.07");
}

.j68vol3fw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 33V18m0-6V9m21 24v-2m0-6V9m.315 30.212v-3.919h1.532");
}

.nbog-pb-i {
  cx: 13.5px;
  cy: 15px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r_qkoabbd {
  cx: 33.734px;
  cy: 39.212px;
  r: 1.081px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uek-bs_mh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.5 5.5h-12a2 2 0 0 0-2 2v33a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-33a2 2 0 0 0-2-2m21 0h-12a2 2 0 0 0-2 2v33a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-33a2 2 0 0 0-2-2");
}

</style>
