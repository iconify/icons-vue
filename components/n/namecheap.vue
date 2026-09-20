<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":142};
const content = `<defs><linearGradient id="SVGgzu0cbGs" x1="13.322%" x2="82.62%" y1="94.945%" y2="1.132%"><stop offset="0%" class="dhn2rmbay"/><stop offset="4.166%" class="qrpliz74w"/><stop offset="17.6%" class="qiwm2rbud"/><stop offset="31.67%" class="ixafbtbjq"/><stop offset="46.35%" class="vvitg1bde"/><stop offset="61.88%" class="eo47lhbig"/><stop offset="78.86%" class="wk5f_mbph"/><stop offset="100%" class="rz86lebdh"/></linearGradient><linearGradient id="SVGcao2lbbR" x1="86.624%" x2="17.326%" y1="5.04%" y2="98.855%"><stop offset="0%" class="dhn2rmbay"/><stop offset="4.166%" class="qrpliz74w"/><stop offset="17.6%" class="qiwm2rbud"/><stop offset="31.67%" class="ixafbtbjq"/><stop offset="46.35%" class="vvitg1bde"/><stop offset="61.88%" class="eo47lhbig"/><stop offset="78.86%" class="wk5f_mbph"/><stop offset="100%" class="rz86lebdh"/></linearGradient></defs><path class="m2o9d3bxs"/><path fill="url(#SVGgzu0cbGs)" class="qrr5f1r_a"/><path fill="url(#SVGcao2lbbR)" class="y5hq9v1pc"/><path class="m1kl-6lhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:namecheap" /></template>
<style>
.dhn2rmbay {
  stop-color: var(--svg-color--d4202c, #d4202c);
}

.eo47lhbig {
  stop-color: var(--svg-color--f69a1e, #f69a1e);
  stop-opacity: 0.381;
}

.ixafbtbjq {
  stop-color: var(--svg-color--eb7123, #eb7123);
  stop-opacity: 0.683;
}

.m1kl-6lhe {
  fill: var(--svg-color--ff8c44, #ff8c44);
  d: path("M87.9 44.6L72.4 14l-.9-1.7c-2.4-4.2-6-7.7-10.4-9.8c1.4-.7 3-1.3 4.5-1.7c1.9-.5 4-.8 6-.8h32.8c9 .1 16.8 5 20.9 12.3l.7 1.7l42.1 83.3l15.5 30.6l.9 1.7c2.4 4.2 6 7.7 10.4 9.8c-1.4.7-3 1.3-4.5 1.7c-1.9.5-4 .8-6.1.8h-32.6c-9-.1-16.8-5-20.9-12.3l-.9-1.7z");
}

.m2o9d3bxs {
  fill: var(--svg-color--ff5000, #ff5000);
  d: path("M232 0c-9 0-16.8 5-20.9 12.3l-.5 1l-18.8 37L168 97.2l15.6 30.7l.9 1.7c2.4 4.2 6 7.7 10.4 9.8c4.4-2.2 8-5.6 10.4-9.8l.9-1.7l46.7-92l1.1-2.2c1.3-3 2-6.2 2-9.7c0-13.3-10.7-24-24-24M87.9 44.6L72.4 14l-.9-1.7c-2.4-4.2-6-7.7-10.4-9.8c-4.4 2.2-8 5.6-10.4 9.8l-.8 1.7l-46.7 92l-1.1 2.2c-1.3 3-2 6.2-2 9.7c0 13.2 10.7 24 24 24c9 0 16.8-5 20.9-12.3l.5-1l18.8-37L88 44.7z");
}

.qiwm2rbud {
  stop-color: var(--svg-color--e25226, #e25226);
  stop-opacity: 0.824;
}

.qrpliz74w {
  stop-color: var(--svg-color--d82d2b, #d82d2b);
  stop-opacity: 0.958;
}

.qrr5f1r_a {
  d: path("M232 0c-9 0-16.9 5-20.9 12.3l-.5 1l-18.8 37L168 97.2l15.6 30.7l.9 1.7c2.4 4.2 6 7.7 10.4 9.8c4.4-2.2 8-5.6 10.4-9.8l.9-1.7l46.7-92l1.1-2.2c1.3-3 2-6.2 2-9.7c0-13.3-10.8-24-24-24");
}

.rz86lebdh {
  stop-color: var(--svg-color--faa71d, #faa71d);
  stop-opacity: 0;
}

.vvitg1bde {
  stop-color: var(--svg-color--f28920, #f28920);
  stop-opacity: 0.536;
}

.wk5f_mbph {
  stop-color: var(--svg-color--f9a41d, #f9a41d);
  stop-opacity: 0.211;
}

.y5hq9v1pc {
  d: path("M24 141.9c9 0 16.9-5 20.9-12.3l.5-1l18.8-37L88 44.7L72.4 14l-.9-1.7c-2.4-4.2-6-7.7-10.4-9.8c-4.4 2.2-8 5.6-10.4 9.8l-.8 1.7l-46.7 92l-1.2 2.3c-1.3 3-2 6.2-2 9.7c0 13.2 10.7 23.9 24 23.9");
}

</style>
