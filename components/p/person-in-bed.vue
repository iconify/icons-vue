<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="jeunsn1yj"><path class="bjo1f1b1r"/><path class="a00npwb7g"/><path class="ebhso62vx"/></g><path class="ka9zo2aml"/><path class="pia2ie41g"/><path class="b2rdg4bxz"/><path class="tay9nfd3r"/><path class="i-c3pjbmx"/><path class="ypqg3da3e"/><path class="i7k0iyb_i"/><path class="q90tb7sse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:person-in-bed" /></template>
<style>
.a00npwb7g {
  d: path("M5 55.3h4V62H5zm50 0h4V62h-4z");
}

.b2rdg4bxz {
  fill: var(--svg-color--ffdd67, #ffdd67);
  d: path("m16.8 35l-.7 1.4l5.3 2.6l2.2-4.6z");
}

.bjo1f1b1r {
  d: path("M6 55c0 .5-.4 1-1 1H3c-.5 0-1-.5-1-1V13c0-.6.5-1 1-1h2c.6 0 1 .4 1 1z");
}

.ebhso62vx {
  d: path("M62 49c0-.5-.4-1-1-1H3c-.5 0-1 .5-1 1v8c0 .5.5 1 1 1h58c.6 0 1-.5 1-1z");
}

.i-c3pjbmx {
  fill: var(--svg-color--ffdd67, #ffdd67);
  d: path("m8 32.2l6.4-6.9c3.7.5 10.4 4.6 7.3 8.9c-.8 1.2-2.8 2.5-5.2 1.4L15 37.7z");
}

.i7k0iyb_i {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M60 38c-.5-.5-27.8-13.7-34.9-8.1l-2 18.1H61s.7-8.1-1-10");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.ka9zo2aml {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("M6 40h20v8H6z");
}

.pia2ie41g {
  fill: var(--svg-color--dae3ea, #dae3ea);
  d: path("M23.5 39.9s-6.3 3.1-14.3.8c-2.5-.7-5.3.9-4.8-.3c1.7-3.6 2.2-11-.1-13.9c-1.6-2.1 3.6-.6 4.5 2.7c2.7 9.8 14.7 6 14.7 10.7");
}

.q90tb7sse {
  fill: var(--svg-color--a53838, #a53838);
  d: path("M30 27.7c-1-1.4-2.6.6-2.6.6s-.7-1-1.6-.6c-.8.4-1.2 1.8-1.2 1.8s-1-1.1-1.5-.3c-8 12.4.9 30.4.9 30.4s-.7-8.1 1.5-10.1c2-1.8 3.4 3.5 3.4 3.5s-.2-7.8.5-8.4c1.6-1.2 2.9 5 2.9 5s2.5-15.4-2.3-21.9");
}

.tay9nfd3r {
  fill: var(--svg-color--eba352, #eba352);
  d: path("M17.1 34c2.4 1.2 5.2-1.6 5.2-1.6c-.2 2 1.3 2 1.3 2c-1 2-4.3 2.5-7.1 1.2z");
}

.ypqg3da3e {
  fill: var(--svg-color--ffbc00, #ffbc00);
  d: path("M7.3 28c-2.9 6 1.8 9.2 5.6 10.1c2.1.5 3.8 0 4.8-.9l-1.3-1.7s-4.8-.6-4.8-4.9c0-1.8 2.6-3.9 2.6-5.4c-.8-.9-5.2-.8-6.9 2.8");
}

</style>
