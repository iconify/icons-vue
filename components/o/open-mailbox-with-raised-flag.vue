<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ff1tlbvvn"/><path class="j7xjeacfg"/><path class="g9jg_gbjr"/><path class="pi1z-cbtb"/><path class="us6f_xb0b"/><path class="tf8947bbs"/><path class="f1uldrzgi"/><path class="un_h3t-3k"/><path class="sxv9iybuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:open-mailbox-with-raised-flag" /></template>
<style>
.f1uldrzgi {
  fill: var(--svg-color--dfe9ef, #dfe9ef);
  d: path("M9.5 16.5L37 13.8c.4 0 .9.2 1.3.5l-5.6 11.9l-2.6 5.8l-6.1-3.8L7.9 17.6c.3-.6.9-1 1.6-1.1");
}

.ff1tlbvvn {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("m38 64l-8.8-1.2v-49H38z");
}

.g9jg_gbjr {
  fill: var(--svg-color--697277, #697277);
  d: path("M17.2 8.5c-1.9 0-3.7.2-5.3.7C4.3 11.3 0 17.9 0 26.8v17l35.7 6.1V29.2c0-10.8-7.6-20.7-18.5-20.7");
}

.j7xjeacfg {
  fill: var(--svg-color--7d8b91, #7d8b91);
  d: path("M44.3 13.8H38V64l6.3-6.1z");
}

.pi1z-cbtb {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M35.7 49.9L0 43.8l35.7-16.3z");
}

.sxv9iybuf {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M37.2 6.4v29.2l2.8-1.3V15.6l11.2-4.3V1.6z");
}

.tf8947bbs {
  fill: var(--svg-color--cad5dd, #cad5dd);
  d: path("m30.1 32l2.6-5.8L44 34.6c-.2.5-.4.9-.8 1L17.6 45c-.7.3-1.4.1-2-.2L24 28.2z");
}

.un_h3t-3k {
  fill: var(--svg-color--333, #333);
  d: path("M46.8 0c-7.4 0-30.3 7.7-34.9 9.2c1.6-.4 3.4-.7 5.3-.7c10.9 0 18.5 9.9 18.5 20.7v20.7l28.3-17V17C64 6.3 57.6 0 46.8 0");
}

.us6f_xb0b {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("m44 34.6l-11.3-8.4l5.6-11.9c.4.4.8 1 1 1.7L44 32.7c.1.7.1 1.4 0 1.9m-36.1-17L24 28.2l-8.5 16.7c-.7-.4-1.3-1.1-1.5-2.1L7.6 20.1c-.2-1-.1-1.8.3-2.5");
}

</style>
