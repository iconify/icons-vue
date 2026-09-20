<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="q1m2erv2p"/><path class="dqurp69yl"/><path class="xc7yq0p0x"/><path class="n_ls0xbme"/><path class="un2l-td4w"/><path class="yjxre7f3q"/><path class="j7iio163o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:pleading-face" /></template>
<style>
.dqurp69yl {
  fill: var(--svg-color--65471b, #65471b);
  d: path("M20.996 28.477a1 1 0 0 1-.309-.049a8.65 8.65 0 0 0-5.375 0a1 1 0 1 1-.617-1.902a10.63 10.63 0 0 1 6.609 0c.525.172.813.736.643 1.26a1 1 0 0 1-.951.691m7.998-18.466A1.005 1.005 0 0 0 28.011 9c-.067-.001-1.653-.056-3.304-1.707a1 1 0 1 0-1.414 1.414C25.56 10.974 27.901 11 28 11a.995.995 0 0 0 .994-.989M12.707 8.707a.998.998 0 0 0-.324-1.63a1 1 0 0 0-1.09.216C9.652 8.934 8.075 8.998 7.99 9A1 1 0 0 0 8 11c.099 0 2.44-.026 4.707-2.293");
}

.j7iio163o {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.337 16.836c1.044-1.046 1.23-2.552.417-3.364c-.813-.813-2.32-.625-3.363.42c-1.045 1.046-1.231 2.552-.418 3.364c.814.813 2.32.625 3.364-.42m3.287 2.845c.46-.459.541-1.12.184-1.477s-1.019-.274-1.478.185c-.458.459-.54 1.12-.183 1.477s1.019.275 1.477-.184Z");
}

.n_ls0xbme {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M24.5 22a5 5 0 1 0 0-10a5 5 0 0 0 0 10");
}

.q1m2erv2p {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.un2l-td4w {
  fill: var(--svg-color--fff, #fff);
  d: path("M24.337 16.836c1.044-1.046 1.23-2.552.417-3.364c-.813-.813-2.32-.625-3.363.42c-1.045 1.046-1.231 2.552-.418 3.364c.814.813 2.32.625 3.364-.42m3.288 2.845c.458-.459.54-1.12.183-1.477s-1.019-.274-1.478.185c-.458.459-.54 1.12-.183 1.477s1.019.275 1.478-.184ZM11.5 23a5.5 5.5 0 1 0 0-11a5.5 5.5 0 0 0 0 11");
}

.xc7yq0p0x {
  fill: var(--svg-color--fff, #fff);
  d: path("M24.5 23a5.5 5.5 0 1 0 0-11a5.5 5.5 0 0 0 0 11");
}

.yjxre7f3q {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M11.5 22a5 5 0 1 0 0-10a5 5 0 0 0 0 10");
}

</style>
