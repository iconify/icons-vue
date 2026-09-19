<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ugt2vubrd"/><path class="t9d_beb9h"/><path class="bbb-9cb0i"/><path class="bapsuabfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:mouth" /></template>
<style>
.bapsuabfq {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M44.4 14.9c-2.5-.8-6.2-.4-11.1 1.6c-.4.2-.8.3-1.3.5c-.4-.2-.9-.3-1.3-.5c-4.9-2-8.6-2.4-11.1-1.6C12.2 17.1 2 32.7 2 32.7c6.3.8 14.5-8.5 30-8.5s23.7 9.3 30 8.5c0 0-10.2-15.6-17.6-17.8");
}

.bbb-9cb0i {
  fill: var(--svg-color--fff, #fff);
  d: path("M58.5 31c0-1.7-11.2-9.9-26.5-9.9S5.5 29.2 5.5 31z");
}

.t9d_beb9h {
  fill: var(--svg-color--60452b, #60452b);
  d: path("M32 20.6L5.9 31.2c6.8 8.3 14.5 5.1 26.1 5.1s19.2 3.1 26.1-5.1z");
}

.ugt2vubrd {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 22.5c-6.3 0-30 10.2-30 10.2c5.6 6.9 3.6 16.8 30 16.8c23.7 0 23.2-8.5 30-16.8c0 0-23.7-10.2-30-10.2");
}

</style>
