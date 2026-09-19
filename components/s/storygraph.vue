<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect class="hlp_znjmy"/><rect class="eqjsp51xq"/><rect transform="rotate(-16.906 34.712 21.264)" class="pw8mkhbub"/><rect class="ytapp3lie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:storygraph" /></template>
<style>
.eqjsp51xq {
  width: 7.603px;
  height: 29.842px;
  x: 16.564px;
  y: 6.617px;
  rx: 1px;
  ry: 1px;
}

.hlp_znjmy {
  width: 7.603px;
  height: 29.842px;
  x: 5.5px;
  y: 6.617px;
  rx: 1px;
  ry: 1px;
}

.pw8mkhbub {
  width: 7.603px;
  height: 29.842px;
  x: 30.911px;
  y: 6.343px;
  rx: 1px;
  ry: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ytapp3lie {
  width: 37px;
  height: 2.828px;
  x: 5.5px;
  y: 39.043px;
  rx: 1px;
  ry: 1px;
}

</style>
