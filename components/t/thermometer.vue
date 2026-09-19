<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ye-l88qur"/><g class="hq2-vcghy"><path class="mkvdnsxhh"/><path class="qoizhdbvz"/></g><ellipse class="z43pzn7ps"/><path class="jny8rcpds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:thermometer" /></template>
<style>
.hq2-vcghy {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

.jny8rcpds {
  fill: var(--svg-color--51575b, #51575b);
  d: path("M30.9 28.2H26l-.1-1.5h4.9zm0 4.2h-4.7v-1.5h4.6zm0 4.2h-4.5v-1.5h4.4zm0 4.2h-4l-.1-1.5h4.1zM31 45h-3.8v-1.4h3.7z");
}

.mkvdnsxhh {
  d: path("m28.4 21.4l1.4 27.5h4.4l1.4-27.5z");
}

.qoizhdbvz {
  d: path("M37.6 53c0 3.1-2.5 5.6-5.6 5.6s-5.6-2.5-5.6-5.6s2.5-5.6 5.6-5.6s5.6 2.5 5.6 5.6");
}

.ye-l88qur {
  fill: var(--svg-color--a1b8c7, #a1b8c7);
  d: path("m37.9 46.2l3.1-36c0-11-18-11-18 0l3.1 36C24.2 47.9 23 50.3 23 53c0 5 4 9 9 9s9-4 9-9c0-2.7-1.2-5.1-3.1-6.8M32 59.8c-3.7 0-6.7-3-6.7-6.8c0-2.4 1.3-4.6 3.3-5.8l-2-37.2c0-6.4 10.8-6.4 10.8 0l-1.9 37.2c1.9 1.2 3.3 3.3 3.3 5.8c0 3.7-3.1 6.8-6.8 6.8");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.z43pzn7ps {
  cx: 32px;
  cy: 21.4px;
  fill: var(--svg-color--a5203c, #a5203c);
  rx: 3.6px;
  ry: 1.2px;
}

</style>
