<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n3nla10dc"/><circle class="muqjdl-qt"/><path class="ciqcz2vor"/><path class="b80yxsb7v"/><circle class="jeb40ebpx"/><circle class="it2cxqb2l"/><path class="k1sprbbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-theater-comedy" /></template>
<style>
.b80yxsb7v {
  fill: currentColor;
  d: path("M11 2v5.5h2V4h8v5c0 2.21-1.79 4-4 4c-.95 0-1.81-.35-2.5-.9v2.35c.76.35 1.61.55 2.5.55c3.31 0 6-2.69 6-6V2z");
}

.ciqcz2vor {
  fill: currentColor;
  d: path("M16.99 9c-1.38 0-2.5.84-2.5 1.88h5c0-1.04-1.12-1.88-2.5-1.88M1 16c0 3.31 2.69 6 6 6s6-2.69 6-6V9H1zm2-5h8v5c0 2.21-1.79 4-4 4s-4-1.79-4-4z");
}

.it2cxqb2l {
  cx: 9px;
  cy: 13.5px;
  r: 1px;
  fill: currentColor;
}

.jeb40ebpx {
  cx: 5px;
  cy: 13.5px;
  r: 1px;
  fill: currentColor;
}

.k1sprbbyp {
  fill: currentColor;
  d: path("M7 17.88c1.38 0 2.5-.84 2.5-1.88h-5c0 1.04 1.12 1.88 2.5 1.88");
}

.muqjdl-qt {
  cx: 15px;
  cy: 6.5px;
  r: 1px;
  fill: currentColor;
}

.n3nla10dc {
  cx: 19px;
  cy: 6.5px;
  r: 1px;
  fill: currentColor;
}

</style>
