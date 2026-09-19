<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="o7lc_xqis"/><path class="r5iw0bceq"/><path class="fyr_a8u6k"/><path class="fbms6ccmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:smiling-face-with-open-mouth-and-closed-eyes" /></template>
<style>
.fbms6ccmw {
  fill: var(--svg-color--fff, #fff);
  d: path("M47 36H17.1c-2.1 0-2.1 4-.1 4h30c2 0 2-4 0-4");
}

.fyr_a8u6k {
  fill: var(--svg-color--ff717f, #ff717f);
  d: path("M24.3 50.7c2.2 1 4.8 1.5 7.7 1.5s5.5-.6 7.7-1.5C37.6 49.6 35 49 32 49s-5.6.6-7.7 1.7");
}

.o7lc_xqis {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M51.7 19.4c.6.3.3 1-.2 1.1c-2.7.4-5.5.9-8.3 2.4c4 .7 7.2 2.7 9 4.8c.4.5-.1 1.1-.5 1c-4.8-1.7-9.7-2.7-15.8-2c-.5 0-.9-.2-.8-.7c1.6-7.3 10.9-10 16.6-6.6m-39.4 0c-.6.3-.3 1 .2 1.1c2.7.4 5.5.9 8.3 2.4c-4 .7-7.2 2.7-9 4.8c-.4.5.1 1.1.5 1c4.8-1.7 9.7-2.7 15.8-2c.5 0 .9-.2.8-.7c-1.6-7.3-10.9-10-16.6-6.6m37.4 15c-.4-.5-1.1-.4-1.9-.4H16.2c-.8 0-1.5-.1-1.9.4C10.4 39.4 15 54 32 54s21.6-14.6 17.7-19.6");
}

.r5iw0bceq {
  fill: var(--svg-color--4c3526, #4c3526);
  d: path("M33.8 41.7c-.6 0-1.5.5-1.1 2c.2.7 1.2 1.6 1.2 2.8c0 2.4-3.8 2.4-3.8 0c0-1.2 1-2 1.2-2.8c.3-1.4-.6-2-1.1-2c-1.6 0-4.1 1.7-4.1 4.6c0 3.2 2.7 5.8 6 5.8s6-2.6 6-5.8c-.1-2.8-2.7-4.5-4.3-4.6");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

</style>
