<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rsrhfac5n"/><path class="xf5r-devq"/><path class="t77avm3lj"/><path class="opp44swht"/><path class="cfrq0ebvd"/><path class="q23740b7t"/><path class="zj2p4py0y"/><path class="bari53b2u"/><path class="af3t0nyrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-off-broken" /></template>
<style>
.af3t0nyrd {
  d: path("M5.33301 12.295C7.39361 10.0709 10.1707 9.09151 12.8624 9.35689");
}

.bari53b2u {
  d: path("M22 2L18.2219 5.77811L14.3625 9.63753L2 22");
}

.cfrq0ebvd {
  d: path("M8.53613 4.68851C11.7518 3.81543 15.1963 4.17863 18.2215 5.77811");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.opp44swht {
  d: path("M2 8.697C2.78923 7.84513 3.64855 7.11499 4.5579 6.50659");
}

.q23740b7t {
  d: path("M20.3213 7.14551C20.9083 7.60771 21.4698 8.12479 21.9997 8.69674");
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.t77avm3lj {
  d: path("M16.7617 10.7051C17.4418 11.1352 18.0826 11.6651 18.666 12.2949");
}

.xf5r-devq {
  d: path("M12.959 14.5083C13.8293 14.7024 14.6585 15.164 15.3339 15.8929");
}

.zj2p4py0y {
  stroke-linejoin: round;
  d: path("M12.0176 19.4644H12.0177");
}

</style>
