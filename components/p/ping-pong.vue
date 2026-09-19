<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="y84t4hxeq"/><path class="gva3igbrv"/><g class="up07qobrn"><path class="nux0i0s7p"/><path class="gsgbvobbm"/></g><path class="wu-nzszvy"/><g class="ozigal3gb"><circle class="gmrqeobbo"/><path class="l1cbpcz4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:ping-pong" /></template>
<style>
.gmrqeobbo {
  cx: 54.1px;
  cy: 54.1px;
  r: 7.9px;
}

.gsgbvobbm {
  d: path("M5.9 61.1c.6.5.9.6 1.5.9c.1-.1.1-.1.2-.1c3.3-3.8 6.9-7.5 8.5-9.1l8.7-9.4l-2.4 1.4z");
}

.gva3igbrv {
  fill: var(--svg-color--fed0ac, #fed0ac);
  d: path("M30.8 49.3L14.6 33.1S18 41 12.2 46.9c0 0-4.9 4.9-10.1 9.4c.6 1.2.4 1.3 2.5 3.5c1.8 1.8 1.9 1.6 2.9 2.2C12 56.7 17 51.7 17 51.7c5.9-5.8 13.8-2.4 13.8-2.4");
}

.l1cbpcz4c {
  d: path("M59.6 51.1c-.4.8-2 .8-3.5 0S53.6 49 54 48.3c.4-.8 2-.8 3.5 0c1.6.8 2.5 2 2.1 2.8");
}

.nux0i0s7p {
  d: path("M7.6 61.8c3.3-3.8 6.9-7.5 8.5-9.1l8.7-9.4l-4.2-4.2l-9.4 8.7C9.5 49.4 5.8 53 2 56.3c.6 1.2.4 1.3 2.5 3.5c1.8 1.8 1.9 1.6 2.9 2.2z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ozigal3gb {
  fill: var(--svg-color--ff8736, #ff8736);
}

.up07qobrn {
  fill: var(--svg-color--d3976e, #d3976e);
}

.wu-nzszvy {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("m30.8 49.3l-6-6l-8.1 8.7c1.6-1.6 6.5-5.3 14.1-2.7M14.6 33.1l6 6l-8.7 8.1c1.6-1.7 5.3-6.5 2.7-14.1");
}

.y84t4hxeq {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M55.3 8.7c-6.2-6.2-20.5-11.9-34.1 1.6c-9 8.9-12.2 20.2 0 32.4c12.2 12.1 23.5 8.9 32.5 0c13.6-13.6 7.8-27.8 1.6-34");
}

</style>
