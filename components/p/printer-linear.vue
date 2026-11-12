<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tlsoow8qq"/><path class="hhlxfkbol"/><path class="si1y-5u0z"/><path class="psk1yp1bz"/><path class="zd0f8hb5r"/><path class="wixyovb7d"/><path class="wex8jf1_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:printer-linear" /></template>
<style>
.hhlxfkbol {
  d: path("M19 14L5 14");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.psk1yp1bz {
  d: path("M15 16.5H9");
}

.si1y-5u0z {
  d: path("M17.9827 6C17.9359 4.44655 17.7626 3.51998 17.1213 2.87868C16.2426 2 14.8284 2 12 2C9.17157 2 7.75736 2 6.87868 2.87868C6.23738 3.51998 6.06413 4.44655 6.01732 6M18 14V16C18 18.8284 18 20.2426 17.1213 21.1213C16.2426 22 14.8284 22 12 22C9.17157 22 7.75736 22 6.87868 21.1213C6 20.2426 6 18.8284 6 16V14");
}

.tlsoow8qq {
  d: path("M9 10H6");
}

.wex8jf1_a {
  d: path("M17.9832 17.9827H18C19.5535 17.9359 20.48 17.7626 21.1213 17.1213C22 16.2426 22 14.8284 22 12C22 9.17157 22 7.75736 21.1213 6.87868C20.2426 6 18.8284 6 16 6H8C5.17157 6 3.75736 6 2.87868 6.87868C2 7.75736 2 9.17157 2 12C2 14.8284 2 16.2426 2.87868 17.1213C3.51998 17.7626 4.44655 17.9359 6 17.9827H6.01681");
}

.wixyovb7d {
  stroke-linejoin: round;
  d: path("M17 10H17.0001");
}

.zd0f8hb5r {
  d: path("M13 19H9");
}

</style>
