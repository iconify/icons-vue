<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dgyle3b0i"/><path class="gl8w5bcja"/><path class="t-l5xu5pe"/><path class="bd25cnc1c"/><path class="t20j6i6uw"/><path class="byjsprtuv"/><path class="b8f_96b9z"/><path class="tc4bz-bjq"/><path class="vdfr-o51h"/><path class="xh13mmqwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:train" /></template>
<style>
.b8f_96b9z {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M8 11C8 2 12.477 1 18 1s10 1 10 10c0 6-4.477 11-10 11c-5.523-.001-10-5-10-11");
}

.bd25cnc1c {
  fill: var(--svg-color--a7a9ac, #a7a9ac);
  d: path("M28 35a1 1 0 0 1-1 1H9a1 1 0 1 1 0-2h18a1 1 0 0 1 1 1m-2-4a1 1 0 0 1-1 1H11a1 1 0 1 1 0-2h14a1 1 0 0 1 1 1");
}

.byjsprtuv {
  fill: var(--svg-color--a7a9ac, #a7a9ac);
  d: path("M18 0C9 0 6 3 6 9v8c0 1.999 3 11 12 11s12-9.001 12-11V9c0-6-3-9-12-9");
}

.dgyle3b0i {
  fill: var(--svg-color--a7a9ac, #a7a9ac);
  d: path("M2 36h32L23 19H13z");
}

.gl8w5bcja {
  fill: var(--svg-color--58595b, #58595b);
  d: path("M5 36h26L21 19h-6z");
}

.t-l5xu5pe {
  fill: var(--svg-color--808285, #808285);
  d: path("M8 36h20l-9-17h-2z");
}

.t20j6i6uw {
  fill: var(--svg-color--58595b, #58595b);
  d: path("M27.076 25.3L23 19H13l-4.076 6.3c1.889 2.517 4.798 4.699 9.076 4.699c4.277 0 7.188-2.183 9.076-4.699");
}

.tc4bz-bjq {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M18 21.999c1.642 0 3.185-.45 4.553-1.228C21.77 19.729 20.03 19 18 19s-3.769.729-4.552 1.772c1.366.777 2.911 1.227 4.552 1.227");
}

.vdfr-o51h {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M19 4.997v4.965c3.488-.232 6-1.621 6-2.463V5.833c0-.791-3.692-.838-6-.836m-2 0c-2.308-.002-6 .044-6 .836V7.5c0 .842 2.512 2.231 6 2.463z");
}

.xh13mmqwt {
  fill: var(--svg-color--269, #269);
  d: path("M6 10s0 3 4 9c0 0-4-2-4-6zm24 0s0 3-4 9c0 0 4-2 4-6z");
}

</style>
