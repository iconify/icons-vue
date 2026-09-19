<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="k6qn5opjd"/><path class="mpf1g2bqe"/><rect class="lrnyqib6g"/><path class="dkl_of00k"/><circle class="flomuibpr"/><path class="lvqxmfbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sony-liv" /></template>
<style>
.dkl_of00k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.611 31.249L27.875 38.5l-2.736-7.251");
}

.flomuibpr {
  cx: 22.187px;
  cy: 27.897px;
  r: 0.75px;
  fill: currentColor;
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

.k6qn5opjd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 10.73a10 10 0 0 0 6.915 9.512l23.17 7.515a10 10 0 0 1 6.915 9.512M24.816 17v-7l4.638 7v-7m6.583 0l-2.319 3.5l-2.319-3.5m2.319 7v-3.5");
}

.lrnyqib6g {
  width: 4.638px;
  height: 7px;
  x: 18.233px;
  y: 10px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.319px;
  ry: 2.319px;
}

.lvqxmfbsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.187 31.249V38.5m-4.798-10.945v9.577c0 .756.612 1.368 1.368 1.368h.41");
}

.mpf1g2bqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.102 16.233c.429.559.967.767 1.716.767h1.036c.965 0 1.747-.782 1.747-1.746v-.008c0-.964-.782-1.746-1.747-1.746h-1.143a1.75 1.75 0 0 1-1.748-1.748h0c0-.968.784-1.752 1.752-1.752h1.03c.75 0 1.288.208 1.717.767");
}

</style>
