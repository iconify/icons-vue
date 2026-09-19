<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="suqcscjsk"/><path class="rkpah_z-d"/><path class="p2a6jb0jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:weary-face" /></template>
<style>
.p2a6jb0jt {
  fill: var(--svg-color--fff, #fff);
  d: path("M43.4 43c.1-.3 0-.6-.2-.8c0 0-2.5-2.2-11.1-2.2S21 42.2 21 42.2c-.2.2-.3.5-.2.8l.2.6c.1.3.4.5.7.5h21c.3 0 .6-.2.7-.5z");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.rkpah_z-d {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M35.8 24.8c2 8.8 10.2 11 16.3 4.4c.3-.3-.2-.6-.7-1.3c-4.9 2.1-11.4.1-14.3-3.8c-.8.2-1.4.2-1.3.7m-24 4.4c6.1 6.6 14.3 4.4 16.3-4.4c.1-.4-.5-.5-1.2-.7c-3.2 4.3-9.9 5.8-14.4 3.9c-.5.5-1 .8-.7 1.2M47.7 44c-1.7-3.6-5.9-6-15.7-6s-14 2.4-15.7 6c-.9 1.9.4 5 .4 5c1.6 3.9 1.4 5 15.3 5s13.6-1.1 15.3-5c0 0 1.3-3.1.4-5");
}

.suqcscjsk {
  fill: var(--svg-color--917524, #917524);
  d: path("M39.4 18.2c3.2 2.7 7.5 3.9 11.7 3.1c.6-.1 1.1 2 .4 2.2c-4.8.9-9.8-.5-13.5-3.6c-.5-.5 1-2 1.4-1.7m-26.5 3c4.2.7 8.5-.4 11.7-3.1c.4-.4 2 1.2 1.4 1.7c-3.7 3.2-8.7 4.5-13.5 3.6c-.7-.2-.2-2.3.4-2.2");
}

</style>
