<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="urg_njbql"/><path class="b3_-i544q"/><path class="lzdz0jb5e"/><path class="m7t_x8bbw"/><path class="y80kmnb3v"/><path class="q44yder-n"/><path class="j4fru1bkt"/><path class="tveeayzyk"/><path class="m3iys3b9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:oeth" /></template>
<style>
.b3_-i544q {
  fill: var(--svg-color--3390f3, #3390f3);
  d: path("M17.611 17.611a7.94 7.94 0 0 0-5.689-13.527a7.94 7.94 0 0 0-5.603 2.357l11.297 11.17z");
}

.ft5dv1b6b {
  fill: none;
}

.j4fru1bkt {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.001 10.941V7.765L14.648 12z");
}

.lzdz0jb5e {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.706 12a5.294 5.294 0 0 1 5.103-5.294l-1.127 1.832A3.71 3.71 0 0 0 8.294 12a3.653 3.653 0 0 0 4.114 3.674l-1.15 1.62A5.284 5.284 0 0 1 6.707 12");
}

.m3iys3b9h {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 16.235v-2.08l-2.646-1.626z");
}

.m7t_x8bbw {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.1 17.294A5.294 5.294 0 0 0 17.294 12a5.26 5.26 0 0 0-4.664-5.294l-.98 1.615c.138-.016.207-.027.35-.027a3.705 3.705 0 0 1 1.477 7.105z");
}

.q44yder-n {
  fill: var(--svg-color--e5f1fe, #e5f1fe);
  d: path("M12.001 13.589V10.94L14.648 12zM12 10.941V7.765L9.355 12z");
}

.tveeayzyk {
  fill: var(--svg-color--e5f1fe, #e5f1fe);
  d: path("M12.001 16.235v-2.08l2.647-1.626z");
}

.urg_njbql {
  fill: var(--svg-color--0074f0, #0074f0);
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.y80kmnb3v {
  fill: var(--svg-color--cee5fd, #cee5fd);
  d: path("M12 13.589V10.94L9.354 12z");
}

</style>
