<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sio6vka1s"/><path class="tyaij6rok"/><path class="vy5waob-q"/><path class="u3xw_g32v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:remote-controller-minimalistic-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sio6vka1s {
  d: path("M19 15V9C19 6.19108 19 4.78661 18.3259 3.77772C18.034 3.34096 17.659 2.96596 17.2223 2.67412C16.2134 2 14.8089 2 12 2C9.19108 2 7.78661 2 6.77772 2.67412C6.34096 2.96596 5.96596 3.34096 5.67412 3.77772C5.08522 4.65907 5.01077 5.8423 5.00136 8M18.8096 19C18.7098 19.4816 18.5577 19.8753 18.3259 20.2223C18.034 20.659 17.659 21.034 17.2223 21.3259C16.2134 22 14.8089 22 12 22C9.19108 22 7.78661 22 6.77772 21.3259C6.34096 21.034 5.96596 20.659 5.67412 20.2223C5 19.2134 5 17.8089 5 15V12");
}

.tyaij6rok {
  d: path("M15 11C15 12.6569 13.6569 14 12 14C10.3431 14 9 12.6569 9 11C9 9.34315 10.3431 8 12 8C13.6569 8 15 9.34315 15 11Z");
}

.u3xw_g32v {
  stroke-linejoin: round;
  d: path("M12 5H12.0001");
}

.vy5waob-q {
  stroke-linejoin: round;
  d: path("M12 17H12.0001");
}

</style>
