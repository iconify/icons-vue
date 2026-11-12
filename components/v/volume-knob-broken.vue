<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wpgm1nb9q"/><path class="x953b1ban"/><path class="aqe2mdwjw"/><path class="nt_-r4bqh"/><path class="gplp858_w"/><path class="idszyhbin"/><path class="h00hr8bwq"/><path class="dyn69sv8m"/><path class="az10qsb-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volume-knob-broken" /></template>
<style>
.aqe2mdwjw {
  stroke-linejoin: round;
  d: path("M6 6H6.0001");
}

.az10qsb-k {
  stroke-linejoin: round;
  d: path("M12 3.5H12.0001");
}

.dyn69sv8m {
  stroke-linejoin: round;
  d: path("M18 6H18.0001");
}

.gplp858_w {
  stroke-linejoin: round;
  d: path("M3.5 12H3.5001");
}

.h00hr8bwq {
  stroke-linejoin: round;
  d: path("M18 18H18.0001");
}

.idszyhbin {
  stroke-linejoin: round;
  d: path("M20.5 12H20.5001");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nt_-r4bqh {
  stroke-linejoin: round;
  d: path("M6 18H6.0001");
}

.wpgm1nb9q {
  d: path("M12 17C9.23858 17 7 14.7614 7 12C7 9.23858 9.23858 7 12 7C14.7614 7 17 9.23858 17 12");
}

.x953b1ban {
  d: path("M12 7V11");
}

</style>
