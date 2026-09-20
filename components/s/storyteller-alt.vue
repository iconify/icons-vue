<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="a3gc-dbxp"/><ellipse transform="rotate(-20 31.982 38.548)" class="lcjixmywq"/><ellipse transform="rotate(-40 39.003 34.495)" class="dyuw4ybyb"/><ellipse transform="rotate(-70 16.017 38.549)" class="pcgf2q92d"/><ellipse transform="rotate(-50 8.997 34.495)" class="mqiggdcti"/><path class="io3ec5qux"/><path class="mk3n33snx"/><path class="fxdz4hxwz"/><path class="xledvxbmb"/><path class="aj8py6b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:storyteller-alt" /></template>
<style>
.a3gc-dbxp {
  cx: 24px;
  cy: 39.956px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.116px;
  ry: 2.351px;
}

.aj8py6b9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.038 32.08c-.591-3.67-1.337-4.788-.982-7.156c.75-2.73 1.65-6.233.817-9.7c-.84-3.499 1.991-5.821 1.991-5.821s-.204 2.961 1.736 5.77c1.94 2.807 2.663 6.113-.204 9.24c-2.859 3.118-1.811 8.764.69 10.538M26.4 5.693s-3.598 3.64-1.94 6.059c2.17 3.165 6.664 3.267 6.964 7.156m-6.126 16.144c-.06.029.264-3.101 4.981-5.385c3.322-1.608 4.117-8.315 4.085-8.317");
}

.dyuw4ybyb {
  cx: 39.003px;
  cy: 34.495px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.116px;
  ry: 2.351px;
}

.fxdz4hxwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.73 34.95c-.136.117-1.434-2.35 1.78-4.87c2.321-1.817 5.412-4.057 5.923-7.351c.388-2.496-2.592-3.677-5.757-4.953");
}

.io3ec5qux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.762 28.594c-.93-.275-2.175-.18-3.374.256c-1.548.563-2.756 1.6-3.068 2.635m4.763 1.749c1.329-.503 2.405-1.358 2.846-2.262m22.988 2.262c-2.092-.792-3.413-2.384-2.976-3.584c.444-1.22 2.535-1.579 4.67-.801c1.55.563 2.757 1.6 3.07 2.635m-23.856-9.709s-.462-1.497-1.228-2.263s-1.532-1.99-1.532-1.99s1.175 3.93-.05 6.075s-.256 4.136.51 5.208s4.748 6.126 4.748 6.126");
}

.lcjixmywq {
  cx: 31.982px;
  cy: 38.548px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.116px;
  ry: 2.351px;
}

.mk3n33snx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.536 20.134s-3.742 3.062-3.023 7.394s4.595 6.893 7.76 7.404m0-.001s3.166.281 7.403.026c4.238-.255 7.353-6.867 7.659-8.756s-.51-4.136-.97-4.85c-.46-.716-.46-2.043-.613-3.37c-.153-1.328 1.379-2.656 1.379-2.656s-1.496.26-3.998 2.302");
}

.mqiggdcti {
  cx: 8.997px;
  cy: 34.495px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.351px;
  ry: 4.116px;
}

.pcgf2q92d {
  cx: 16.017px;
  cy: 38.549px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.351px;
  ry: 4.116px;
}

.xledvxbmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.433 22.729s2.553-3.727-.51-7.76c-3.064-4.034-4.29-3.285-3.523-9.276c0 0-4.85 2.74-4.136 6.825c.715 4.084 3.012 4.34 2.86 7.71c-.154 3.369-.065 3.912-5.426 9.58");
}

</style>
