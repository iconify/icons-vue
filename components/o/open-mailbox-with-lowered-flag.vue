<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ff1tlbvvn"/><path class="j7xjeacfg"/><path class="lb2mnwy_k"/><path class="y6jfeezih"/><path class="j-kaywbyz"/><path class="flogfzbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:open-mailbox-with-lowered-flag" /></template>
<style>
.ff1tlbvvn {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("m38 64l-8.8-1.2v-49H38z");
}

.flogfzbgn {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("m62.7 14.2l-26 12.4v3.3l19.2-9.6v9.9l6.8-3.8z");
}

.j-kaywbyz {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M35.7 49.9L0 43.8l35.7-16.4z");
}

.j7xjeacfg {
  fill: var(--svg-color--7d8b91, #7d8b91);
  d: path("M44.3 13.8H38V64l6.3-6.1z");
}

.lb2mnwy_k {
  fill: var(--svg-color--333, #333);
  d: path("M46.8 0c-8.2 0-35.6 9.5-35.6 9.5l24.6 40.4l28.3-17V17C64 6.3 57.6 0 46.8 0");
}

.y6jfeezih {
  fill: var(--svg-color--697277, #697277);
  d: path("M17.2 8.5C6.4 8.5 0 16 0 26.8v17l35.7 6.1V29.2c0-10.8-7.6-20.7-18.5-20.7");
}

</style>
