<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="deoagybxw"/><path class="bmfk0b-ol"/><path class="hslwj9b5u"/><path class="og12ncb9n"/><path class="xweqkv_ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:womans-boot" /></template>
<style>
.bmfk0b-ol {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M54.5 50.3c-15.2-5.5-23.3-10.6-24.2-36.1l-21.9-.4C10 33.3 6.3 28 5.4 39.3c-.4 5.3 3.5 10 10.4 10c8.9 0 15.9 9.5 17.5 9.5h24.6s2.5-6.3-3.4-8.5");
}

.deoagybxw {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M58.6 58.8c-5.5 0-50.7-15.1-50.7-15.1L9.4 62h6.3s.1-5.8 1-8.7c8.2 0 12.4 8.7 15.6 8.7h26.3c.5 0 .5-3.2 0-3.2");
}

.hslwj9b5u {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M13.8 11.1H16V33h-2.2z");
}

.og12ncb9n {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M34 2.7H5L6.2 14s4.3 1.6 13.2 1.6c8 0 13.2-.8 13.2-.8z");
}

.xweqkv_ei {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M19.5 2C13.7 2 5 2.3 5 2.7s8.7.7 14.5.7S34 3.1 34 2.7S25.3 2 19.5 2");
}

</style>
