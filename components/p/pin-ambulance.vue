<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bwvyyfx1o"/><path class="cneoforuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-ambulance" /></template>
<style>
.bwvyyfx1o {
  d: path("M11.999 14.5H2.5V5q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119t.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4 3.5h10L19.5 9v.501");
}

.cneoforuh {
  d: path("M4.5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7.466-1.927q-.157.043-.305.111q-.148.069-.283.16t-.253.203t-.217.242t-.175.274t-.128.298t-.079.315t-.026.324q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01q.14 0 .278-.019M8 6.25v5m-2.5-2.5h5M18 21l-2.25-3.25a3.25 3.25 0 1 1 4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
