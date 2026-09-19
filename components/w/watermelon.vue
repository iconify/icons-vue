<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="btkk72idz"/><path class="wjx3opb2s"/><path class="mpcz69biy"/><path class="lqs7dccmw"/><path class="a5z--k0cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:watermelon" /></template>
<style>
.a5z--k0cs {
  fill: var(--svg-color--64892f, #64892f);
  d: path("M28.2 54.7v7.1q3.75.3 7.5 0v-7.1c-2.4.2-5 .2-7.5 0m-17.6-5.3l-2.2 5.8c2.1 1.4 4.4 2.5 6.7 3.5l2.3-6.2c-2.3-.8-4.6-1.9-6.8-3.1m42.8 0c-2.2 1.2-4.5 2.3-6.9 3.1l2.3 6.2c2.3-1 4.6-2.1 6.7-3.5z");
}

.btkk72idz {
  fill: var(--svg-color--f55, #f55);
  d: path("M2.1 50.3c16.2 15.6 43.6 15.6 59.8-.1L32 2z");
}

.lqs7dccmw {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M16 38.5c0-1.3 2.4-4.6 2.4-4.6s2.5 3.4 2.5 4.7s-1 2.3-2.4 2.3s-2.5-1.1-2.5-2.4m12.4 4.6c0-1.3 2.4-4.6 2.4-4.6s2.5 3.4 2.5 4.7s-1 2.3-2.4 2.3s-2.5-1.1-2.5-2.4m8.1-11.6c0-1.3 2.4-4.6 2.4-4.6s2.5 3.4 2.5 4.7s-1 2.3-2.4 2.3s-2.5-1.1-2.5-2.4m8.2 11c0-1.3 2.4-4.6 2.4-4.6s2.5 3.4 2.5 4.7s-1 2.3-2.4 2.3c-1.4-.1-2.5-1.1-2.5-2.4M27.2 20.9c0-1.3 2.4-4.6 2.4-4.6S32 19.7 32 21s-1 2.3-2.4 2.3c-1.3-.1-2.4-1.1-2.4-2.4");
}

.mpcz69biy {
  fill: var(--svg-color--8cc63e, #8cc63e);
  d: path("M4.9 45.6L2 50.2c16.2 15.7 43.7 15.7 60-.1l-2.8-4.6C43.7 58 20.3 58 4.9 45.6");
}

.wjx3opb2s {
  fill: var(--svg-color--ceff80, #ceff80);
  d: path("m6 44l-1.1 1.6c11.8 10.4 36.8 14.5 54.3-.1L58 44C42.9 55.5 21.1 55.5 6 44");
}

</style>
