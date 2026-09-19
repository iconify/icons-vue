<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="m0ejqsbbi"/><g class="jeunsn1yj"><path class="azsh60b8o"/><path class="dvtd9q9op"/></g><path class="dp9z47bpm"/><path class="o564bebgx"/><path class="zry_9yv1f"/><path class="bzq_xdb8u"/><path class="x7_is3bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:penguin" /></template>
<style>
.azsh60b8o {
  d: path("M10.4 27C-.4 33.7 1.7 43 3.3 41.9C20 29.7 24.2 18.5 10.4 27m43.2 0c-13.8-8.5-9.6 2.7 7.1 14.9c1.6 1.1 3.7-8.2-7.1-14.9");
}

.bzq_xdb8u {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("m37 22.3l-5 1.2l-5-1.2c0-3.2 2.2-5.7 5-5.7s5 2.6 5 5.7");
}

.dp9z47bpm {
  fill: var(--svg-color--fff, #fff);
  d: path("M44 18.8c0-12.4-10.1-10-10.1-.7h-3.7C30.1 8.8 20 6.4 20 18.8c0 9.7-4 15.7-4 22.1C16 52.5 23.7 58 32 58s16-5.6 16-17.1c0-6.4-4-12.4-4-22.1");
}

.dvtd9q9op {
  d: path("M48 17.5C48 8.9 40.8 2 32 2S16 8.9 16 17.5c0 11.6-4 15.5-4 23.2C12 51.3 21 60 32 60s20-8.7 20-19.3c0-7.7-4-11.6-4-23.2");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.m0ejqsbbi {
  fill: var(--svg-color--e08828, #e08828);
  d: path("M26.3 60.5c-.8 0-2.6.7-3.2.1c-.8-.8 0-4.6 0-4.6h-2.3s.8 3.8 0 4.6c-.6.5-2.4-.1-3.2-.1c-2 0-3.7 1.5-3.7 1.5h16c.1 0-1.5-1.5-3.6-1.5m20 0c-.8 0-2.6.7-3.2.1c-.8-.8 0-4.6 0-4.6h-2.3s.8 3.8 0 4.6c-.6.5-2.4-.1-3.2-.1c-2 0-3.7 1.5-3.7 1.5h16c.1 0-1.5-1.5-3.6-1.5");
}

.o564bebgx {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M41 17c0 1.7-.9 3-2 3s-2-1.3-2-3s.9-3 2-3s2 1.3 2 3m-14 0c0 1.7-.9 3-2 3s-2-1.3-2-3s.9-3 2-3s2 1.3 2 3");
}

.x7_is3bgx {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M33.7 17.8c.3.3.4.7.3.9s-.5 0-.8-.3s-.4-.7-.3-.9c.2-.1.6 0 .8.3m-3.4 0c-.3.3-.4.7-.3.9s.5 0 .8-.3s.4-.7.3-.9c-.2-.1-.6 0-.8.3");
}

.zry_9yv1f {
  fill: var(--svg-color--e08828, #e08828);
  d: path("M28 22h8c0 2.5-1.8 4.6-4 4.6s-4-2-4-4.6");
}

</style>
