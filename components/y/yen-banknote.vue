<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="eqdeu_bmw"/><path class="hrmcw2b7j"/><circle class="q4kff4p4q"/><path class="s49x_wgnx"/><path class="g_wpugbvv"/><path class="yb_b0wbvq"/><path class="x16voubbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:yen-banknote" /></template>
<style>
.eqdeu_bmw {
  fill: var(--svg-color--9e7e54, #9e7e54);
  d: path("M119.65 102.09H8.35c-2.4 0-4.35-1.95-4.35-4.35V30.28c0-2.41 1.95-4.37 4.37-4.37h111.27c2.41 0 4.37 1.95 4.37 4.37v67.46a4.37 4.37 0 0 1-4.36 4.35");
}

.g_wpugbvv {
  fill: var(--svg-color--ffecb3, #ffecb3);
  d: path("M53 25.91h22.01v76.18H53z");
}

.hrmcw2b7j {
  fill: var(--svg-color--f7b95e, #f7b95e);
  d: path("M119.78 89.91H8.22A4.22 4.22 0 0 1 4 85.69V30.28c0-2.41 1.95-4.37 4.37-4.37h111.27c2.41 0 4.37 1.95 4.37 4.37v55.41a4.236 4.236 0 0 1-4.23 4.22");
}

.q4kff4p4q {
  cx: 84.78px;
  cy: 57.91px;
  r: 18.5px;
  fill: var(--svg-color--9e7e54, #9e7e54);
  opacity: var(--svg-opacity--0-5, 0.5);
}

.s49x_wgnx {
  fill: var(--svg-color--9e7e54, #9e7e54);
  d: path("M106.45 33.1c.86 5.4 5.14 9.68 10.54 10.54v28.54c-5.4.86-9.68 5.14-10.54 10.54H21.42c-1.1-5.11-5.26-9.05-10.42-9.87V44.31c5.63-.89 10.03-5.49 10.63-11.21zm1.84-2h-88.6c.01.22.02.44.02.67c0 5.91-4.79 10.7-10.7 10.7V74.7c5.68 0 10.33 4.43 10.68 10.03h88.61c0-5.91 4.79-10.7 10.7-10.7V41.8c-5.92 0-10.71-4.79-10.71-10.7");
}

.x16voubbk {
  fill: var(--svg-color--ffc06c, #ffc06c);
  d: path("M53 89.91h22.01v12.18H53z");
}

.yb_b0wbvq {
  fill: var(--svg-color--fff, #fff);
  d: path("m36.52 55.47l6.16-13.25c.17-.37.55-.61.96-.61h3.05c.48 0 .78.5.57.93l-7.3 14.31c-.21.41.09.89.55.89h4.13c.4 0 .72.32.72.72v1.36c0 .4-.32.72-.72.72h-5.92c-.34 0-.62.28-.62.62v2.45c0 .34.28.62.62.62h5.92c.4 0 .72.32.72.72v1.34c0 .4-.32.72-.72.72h-5.92c-.34 0-.62.28-.62.62v5.79c0 .44-.36.8-.8.8h-2.72c-.44 0-.8-.36-.8-.8v-5.79c0-.34-.28-.62-.62-.62h-5.79c-.4 0-.72-.32-.72-.72v-1.34c0-.4.32-.72.72-.72h5.79c.34 0 .62-.28.62-.62v-2.45c0-.34-.28-.62-.62-.62h-5.79c-.4 0-.72-.32-.72-.72v-1.36c0-.4.32-.72.72-.72h4.17c.46 0 .75-.48.55-.89l-7.3-14.31c-.22-.42.09-.93.57-.93h3.12c.41 0 .79.24.96.61l6.16 13.25c.18.39.74.39.92 0");
}

</style>
