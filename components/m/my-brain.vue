<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="roerd7bal"/><path class="icleb_bhq"/><path class="xd4ttzbag"/><path class="lel4kfb5k"/><path class="fdfnfkbyb"/><path class="gij3ywbfc"/><path class="r4bxrbc0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-brain" /></template>
<style>
.fdfnfkbyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.303 11.386L5.5 22.6v8.409l2.803 8.409l5.606 2.803l8.41-5.606V19.796l-5.607 8.409l-2.803-11.213L5.5 22.6l11.212 5.606l5.606 8.409");
}

.gij3ywbfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.318 36.614H13.91L5.5 31.008");
}

.icleb_bhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.697 11.386L42.5 22.6v8.409l-2.803 8.409l-5.606 2.803l-8.41-5.606V19.796l5.607 8.409l2.803-11.213L42.5 22.6l-11.212 5.606l-5.606 8.409");
}

.lel4kfb5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.894 25.402L34.09 36.614l-2.803-8.41m-8.969-8.408L19.515 8.583L13.91 5.78l-5.606 5.606l5.606 5.606ZM13.91 5.78l8.408 14.015");
}

.r4bxrbc0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.106 25.402l2.803 11.212l2.803-8.41");
}

.roerd7bal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.682 19.796l2.803-11.213L34.09 5.78l5.606 5.606l-5.606 5.606ZM34.09 5.78l-8.408 14.016");
}

.xd4ttzbag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.682 36.614h8.409l8.409-5.606");
}

</style>
