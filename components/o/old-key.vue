<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="k7h88hbvj"/><path class="tz2wr-b3x"/><path class="ki215db2e"/><path class="qrfzzfbnl"/><path class="tixloxb-t"/><path class="r9i-26boo"/><circle class="um13vxe1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:old-key" /></template>
<style>
.k7h88hbvj {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M7.915 34.868c.725.725 1.313 1.313 2.417.21s-.665-2.871.439-3.975l.552-.552c1.104-1.104 2.872.664 3.974-.438c1.104-1.104.516-1.692-.21-2.417L12.41 25.02c-.725-.725-1.808-.819-2.417-.209l-4.964 4.964c-.61.609-.516 1.692.209 2.417z");
}

.ki215db2e {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M16.919 3.743a5.5 5.5 0 1 0 7.778 7.779a5.5 5.5 0 0 0-7.778-7.779m6.363 6.364a3.5 3.5 0 1 1-4.95-4.95a3.5 3.5 0 0 1 4.95 4.95");
}

.qrfzzfbnl {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M26.111 1.622A5.5 5.5 0 1 0 33.888 9.4a5.5 5.5 0 0 0-7.777-7.778m6.364 6.364a3.5 3.5 0 1 1-4.949-4.952a3.5 3.5 0 0 1 4.949 4.952");
}

.r9i-26boo {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M19.394 18.238a2 2 0 0 1-2.829 2.829l-2.829-2.829a2 2 0 1 1 2.829-2.828z");
}

.tixloxb-t {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M23.989 10.814a5.5 5.5 0 1 0 7.778 7.779a5.5 5.5 0 0 0-7.778-7.779m6.365 6.364a3.5 3.5 0 1 1-4.95-4.95a3.5 3.5 0 0 1 4.95 4.95");
}

.tz2wr-b3x {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M1.03 33.772a2 2 0 0 0 2.829 0l19.07-19.069c-.101-2.727 4.95-4.95 3.536-6.364c-.781-.781-4.243 5.657-6.971 4.142L1.03 30.944a2 2 0 0 0 0 2.828");
}

.um13vxe1c {
  cx: 26px;
  cy: 9px;
  r: 1px;
  fill: var(--svg-color--31373d, #31373d);
}

</style>
