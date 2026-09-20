<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGADQeseka"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="xrvcv-bjh"/><path class="g170_cc4l"/></g></mask></defs><circle mask="url(#SVGADQeseka)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:t-shirt-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.g170_cc4l {
  d: path("M14.5 13.5a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2z");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.xrvcv-bjh {
  fill-rule: evenodd;
  d: path("M5.448 13.397L6 13.12V20a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3v-6.882l.553.276a1 1 0 0 0 1.423-.677l1-4.5a1 1 0 0 0-.269-.924l-2.414-2.414A3 3 0 0 0 18.172 4H16a1 1 0 0 0-.985.83C14.747 6.382 14.128 7 12.999 7s-1.747-.618-2.013-2.17A1 1 0 0 0 10 4H7.829a3 3 0 0 0-2.122.88L3.295 7.292a1 1 0 0 0-.27.923l.999 4.503a1 1 0 0 0 1.424.678m1.673-7.104A1 1 0 0 1 7.83 6h1.377c.57 1.928 1.871 3 3.793 3s3.223-1.072 3.795-3h1.378a1 1 0 0 1 .707.293l2.026 2.026l-.603 2.714l-.855-.427A1 1 0 0 0 18 11.5V20a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-8.5a1 1 0 0 0-1.448-.894l-.853.428l-.602-2.715z");
}

</style>
