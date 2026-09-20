<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="woagv5bji"/><path class="koufdk74g"/><path class="uw0tn4qbi"/><path class="rrwm8uaph"/><path class="j2d9j4b0r"/><path class="miurf-h0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weed-duotone-bold" /></template>
<style>
.j2d9j4b0r {
  d: path("M12 12 8 8h4L8 4");
}

.koufdk74g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12 8 8h4L8 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.miurf-h0g {
  d: path("M5 18h14");
}

.rrwm8uaph {
  d: path("M12 4v14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uw0tn4qbi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 18h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.woagv5bji {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
