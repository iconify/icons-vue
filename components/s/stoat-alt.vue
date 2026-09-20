<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cmu14zbxw"/><path class="uhne7iymw"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stoat-alt" /></template>
<style>
.cmu14zbxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.648 18.877l4.305-.377M17.8 27.668v-8.979m16.381-1.433l4.319-.378m-2.16 9.168v-8.979m-14.717 3.44c0-1.189.963-2.237 2.152-2.341s2.153.775 2.153 1.964v4.675c0 1.188-.964 2.236-2.153 2.34s-2.152-.775-2.152-1.964zm10.85 3.739c0 1.189-.956 2.236-2.136 2.34c-1.196.104-2.165-.78-2.165-1.976v-1.25c0-1.191.974-2.25 2.165-2.355c1.25-.11 2.14-.03 2.14-.03M9.5 26.47c0 1.063.859 1.85 1.919 1.757l.473-.042c1.057-.092 1.913-1.027 1.913-2.087v-.65c0-1.06-.856-1.845-1.913-1.753l-.477.042c-1.058.093-1.915-.693-1.915-1.754v-.643c0-1.063.859-2 1.919-2.093l.468-.04c1.06-.094 1.918.693 1.918 1.756");
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

.uhne7iymw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.508 19.415c.097-1.236.68-1.723 1.816-1.822l.27-.024c1.136-.099 1.883.336 1.883 1.687v7.142M9.5 31.122l29-2.537");
}

</style>
