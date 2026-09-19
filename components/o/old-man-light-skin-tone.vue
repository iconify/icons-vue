<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="scxntnb6n"/><path class="ax2ujobkr"/><path class="b_16s327s"/><g class="cgvivj-gr"><path class="n_11zedyy"/><circle class="h4nexb-st"/></g><circle class="jg05zueih"/><circle class="gnbejzb3a"/><circle class="k34n1uble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:old-man-light-skin-tone" /></template>
<style>
.ax2ujobkr {
  fill: var(--svg-color--ffe1bd, #ffe1bd);
  d: path("M58.5 36.8c-9.1-3.6-2-13.5-1.7-15.5C56.8 21.3 54.7 2 32 2S7.2 21.3 7.2 21.3c.3 2 7.5 11.9-1.7 15.5c0 0-3.4-.4-3.4 3.7c0 4.9 3.5 4.1 3.5 4.1C5.6 52.1 13 62 32 62s26.4-9.9 26.4-17.4c0 0 3.5.8 3.5-4.1c0-4.1-3.4-3.7-3.4-3.7");
}

.b_16s327s {
  fill: var(--svg-color--748a93, #748a93);
  d: path("M40.7 52.9c.2 0 .3-.9.3-1.3c0-2.6-4-4.8-9-4.8s-9 2.3-9 4.9c0 .3.1 1.2.2 1.2zM17.6 9.8c2.3-.7 4.7-1.5 7.1-2s4.9-.9 7.3-1c2.5-.1 5 .1 7.4.6s4.8 1.3 7 2.4c-2.4-.4-4.8-.8-7.2-.9c-2.4-.2-4.8-.2-7.1-.1c-2.4.1-4.8.3-7.2.5s-4.8.5-7.3.5M14.5 14c2.9-.7 5.7-1.5 8.6-2s5.9-.9 8.9-1s6 .1 8.9.6c3 .5 5.9 1.2 8.6 2.4c-2.9-.4-5.8-.7-8.8-.9c-2.9-.2-5.8-.2-8.7-.1s-5.8.3-8.7.5s-5.8.6-8.8.5");
}

.cgvivj-gr {
  fill: var(--svg-color--454749, #454749);
}

.gnbejzb3a {
  cx: 44.3px;
  cy: 37.9px;
  r: 9px;
  fill: var(--svg-color--454749, #454749);
}

.h4nexb-st {
  cx: 19.7px;
  cy: 37.9px;
  r: 9px;
}

.jg05zueih {
  cx: 19.7px;
  cy: 37.9px;
  r: 6px;
  fill: var(--svg-color--b4d7ee, #b4d7ee);
}

.k34n1uble {
  cx: 44.3px;
  cy: 37.9px;
  r: 6px;
  fill: var(--svg-color--b4d7ee, #b4d7ee);
}

.n_11zedyy {
  d: path("m17.8 39.3l-.3-3c.8-.1 1.9-.3 3.1-.5c5.9-1.1 15.7-3 26.4.6l-1 2.8c-9.9-3.4-19.2-1.6-24.8-.5c-1.4.3-2.6.5-3.4.6");
}

.scxntnb6n {
  fill: var(--svg-color--748a93, #748a93);
  d: path("M32.1 8.9s-.1 0 0 0h-.2C6.9 8.9 2 17.7 2 31.5l.9 9.4h58.3l.9-9.4c-.1-13.8-5-22.6-30-22.6");
}

</style>
