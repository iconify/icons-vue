<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGfIvHIbRZ)" class="j2e-uwb-b"/><path class="we6bmhb9c"/><path fill="url(#SVGm32NN1WY)" class="vkzkf3bek"/><defs><linearGradient id="SVGfIvHIbRZ" x1="21" x2="3" y1="12.016" y2="12.016" gradientUnits="userSpaceOnUse"><stop offset=".11" class="ab49cibdr"/><stop offset=".2" class="n2jqz6pop"/><stop offset=".35" class="x0nbll51i"/><stop offset=".46" class="pwmcsebhe"/><stop offset=".7" class="g499chlgl"/><stop offset="1" class="nljkssbui"/></linearGradient><linearGradient id="SVGm32NN1WY" x1="9.644" x2="7.743" y1="16.304" y2="16.388" gradientUnits="userSpaceOnUse"><stop class="t9dkn6_og"/><stop offset="1" class="r2caf12fb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sdao" /></template>
<style>
.ab49cibdr {
  stop-color: var(--svg-color--e25900, #e25900);
}

.ft5dv1b6b {
  fill: none;
}

.g499chlgl {
  stop-color: var(--svg-color--2024de, #2024de);
}

.j2e-uwb-b {
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m2.276-11.53c.207-.895.09-2.05-1.016-3.632c3.976.868 6.49 5.193 5.41 9.047a6.82 6.82 0 0 1-3.234 4.225c-1.329.741-3.267 1.323-4.701.54a2.71 2.71 0 0 1-1.33-2.79c.176-.873.806-1.731 1.478-2.541c.36-.434.741-.847 1.117-1.27l.582-.641c.752-.853 1.435-1.864 1.684-2.939z");
}

.n2jqz6pop {
  stop-color: var(--svg-color--cbc91e, #cbc91e);
}

.nljkssbui {
  stop-color: var(--svg-color--2624df, #2624df);
}

.pwmcsebhe {
  stop-color: var(--svg-color--3093d3, #3093d3);
}

.r2caf12fb {
  stop-color: var(--svg-color--2133dd, #2133dd);
  stop-opacity: 0.4;
}

.t9dkn6_og {
  stop-color: var(--svg-color--203bdb, #203bdb);
}

.vkzkf3bek {
  d: path("M15.44 19.11c-1.328.74-3.266 1.323-4.7.54a2.71 2.71 0 0 1-1.33-2.79c.175-.874.805-1.732 1.478-2.542c.36-.434.74-.847 1.117-1.27l.582-.64c-.995 1.047-2.51 1.561-3.6 2.403c-1.085.83-1.43 2.086-1.143 3.425c.301 1.376 1.328 2.647 3.806 2.753c1.551.069 2.764-.953 3.79-1.88");
}

.we6bmhb9c {
  fill: var(--svg-color--203bdb, #203bdb);
  d: path("M6.203 8.293c3.15-3.378 7.026-2.457 7.026-2.457l-.075-.084c-.423-.106-4.33-.794-6.95 2.54");
}

.x0nbll51i {
  stop-color: var(--svg-color--2de2c1, #2de2c1);
}

</style>
