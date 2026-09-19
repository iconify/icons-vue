<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jm8-5lslf"/><circle class="f2yjju4lp"/><path class="j7p47fbty"/></g><g class="y9tr6bcfx"><path class="lt-z35bab"/><circle class="r5jyf5bvc"/><path class="bscad0wqd"/><circle class="v57zdob7j"/><path class="m9pitrdcz"/><circle class="v_ufj67xs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:niagara-widgets-for-kwgt" /></template>
<style>
.bscad0wqd {
  d: path("M18.979 24h17");
}

.f2yjju4lp {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
}

.j7p47fbty {
  d: path("M36.654 34.492v8.016m3.692 0v-2.053L38.273 38.5l2.073-1.955v-2.053");
}

.jm8-5lslf {
  d: path("M33.43 43.327A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24a21.4 21.4 0 0 1-2.174 9.431");
}

.lt-z35bab {
  d: path("M18.979 18h17");
}

.m9pitrdcz {
  d: path("M18.979 30h17");
}

.r5jyf5bvc {
  cx: 14.021px;
  cy: 18px;
  r: 2px;
}

.v_ufj67xs {
  cx: 14.021px;
  cy: 30px;
  r: 2px;
}

.v57zdob7j {
  cx: 14.021px;
  cy: 24px;
  r: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
