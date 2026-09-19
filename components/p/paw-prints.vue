<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g transform="translate(4)" class="xal446b1e"><path class="kgp4xbcuc"/><ellipse transform="rotate(-8.66 16.733 5.904)" class="o2ac3tbhz"/><path class="vha2hibkh"/><ellipse transform="rotate(-31.471 6.702 10.27)" class="s3gpu8k4q"/><path class="ruylwopip"/></g><g transform="translate(4)" class="xal446b1e"><path class="sag8kd0_v"/><ellipse transform="rotate(-131.721 52.102 54.08)" class="o2l_mvf3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:paw-prints" /></template>
<style>
.kgp4xbcuc {
  d: path("M29.25 21.12c.765 5.03-3.527 5.59-9.36 6.479c-5.846.889-11.02 1.772-11.781-3.256c-.769-5.04 3.342-9.836 9.183-10.728c5.835-.887 11.193 2.467 11.958 7.505");
}

.o2ac3tbhz {
  cx: 16.728px;
  cy: 5.903px;
  rx: 3.669px;
  ry: 5.943px;
}

.o2l_mvf3x {
  cx: 52.11px;
  cy: 54.08px;
  rx: 2.502px;
  ry: 4.301px;
}

.ruylwopip {
  d: path("M5.288 16.871c1.771 1.583 2.462 3.701 1.544 4.734c-.92 1.028-3.105.582-4.875-.998c-1.774-1.583-2.464-3.7-1.546-4.731c.922-1.031 3.106-.586 4.877.995");
}

.s3gpu8k4q {
  cx: 6.71px;
  cy: 10.271px;
  rx: 3.052px;
  ry: 5.245px;
}

.sag8kd0_v {
  d: path("M26.484 56.46c-.767 5.03 3.527 5.59 9.361 6.479c5.846.89 11.01 1.774 11.781-3.256c.769-5.04-3.343-9.834-9.183-10.727c-5.836-.889-11.192 2.468-11.959 7.504m8.886-15.767c-.496 3.243.726 6.121 2.731 6.429c2 .302 4.03-2.08 4.519-5.325c.496-3.246-.726-6.123-2.729-6.427c-2-.308-4.03 2.077-4.521 5.323m-9.643 2.812c.951 2.732 3.01 4.508 4.606 3.954c1.592-.552 2.113-3.219 1.164-5.954c-.951-2.738-3.01-4.508-4.604-3.96c-1.592.554-2.117 3.219-1.166 5.96m20.693.515c-1.511 2.468-1.573 5.188-.132 6.069c1.437.879 3.828-.413 5.338-2.884c1.513-2.471 1.575-5.191.136-6.067c-1.439-.88-3.83.41-5.342 2.882");
}

.vha2hibkh {
  d: path("M30 8.163c-.951 2.734-3.01 4.507-4.606 3.954c-1.592-.551-2.113-3.22-1.164-5.954c.949-2.74 3.01-4.51 4.604-3.961c1.592.553 2.113 3.22 1.166 5.961");
}

.xal446b1e {
  fill: var(--svg-color--ed2e7c, #ed2e7c);
}

</style>
