<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jehw8hlyz"/><path class="cv3a5gb2d"/><path class="z7y5weydc"/><path class="inqo7obdq"/><path class="qiwkhebwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:sparkler" /></template>
<style>
.cv3a5gb2d {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M30.9 32h2.2v32h-2.2z");
}

.inqo7obdq {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m25.3 52.5l2.5-14.7l-13.3 6.9l10.7-10.5L10.4 32l14.8-2.2l-10.7-10.5l13.3 6.9l-2.5-14.7L32 24.8l6.7-13.3l-2.5 14.7l13.3-6.9l-10.7 10.5L53.6 32l-14.8 2.2l10.7 10.5l-13.3-6.9l2.5 14.7L32 39.2z");
}

.jehw8hlyz {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M0 0h64v64H0z");
}

.qiwkhebwr {
  fill: var(--svg-color--fff, #fff);
  d: path("m41.5 18.9l-5.1 9.9l11-1.8l-10 5l10 5l-11-1.8l5.1 9.9l-7.8-8L32 48.2l-1.7-11.1l-7.8 8l5.1-9.9l-11 1.8l10-5l-10-5l11 1.8l-5.1-9.9l7.8 8L32 15.8l1.7 11.1z");
}

.z7y5weydc {
  fill: var(--svg-color--ffdd7d, #ffdd7d);
  d: path("m32 3.2l3 19.7L48.9 8.7l-9.1 17.7l19.6-3.3L41.6 32l17.8 8.9l-19.6-3.3l9.1 17.7L35 41.1l-3 19.7l-3-19.7l-13.9 14.2l9.1-17.7l-19.6 3.3L22.4 32L4.6 23.1l19.6 3.3l-9.1-17.7L29 22.9z");
}

</style>
