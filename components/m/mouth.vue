<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lwvz41bmg"/><path class="fh0-eu4eq"/><path class="i0df4sb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:mouth" /></template>
<style>
.fh0-eu4eq {
  fill: var(--svg-color--662113, #662113);
  d: path("M28.389 15.5C23.963 14.035 21 13.417 18 13.417s-5.962.618-10.389 2.083C3.833 16.75 1 16.167 1 17c0 .834 9 5 17 5s17-4.166 17-5s-2.834-.25-6.611-1.5");
}

.i0df4sb5e {
  fill: var(--svg-color--fff, #fff);
  d: path("M28.389 15.5C23.963 14.035 21 13.417 18 13.417s-5.962.618-10.389 2.083c-3.624 1.199-6.371.715-6.59 1.408c2.454.385 9.119-.644 16.979-.644s14.524 1.029 16.979.644c-.219-.693-2.967-.209-6.59-1.408");
}

.lwvz41bmg {
  fill: var(--svg-color--e75a70, #e75a70);
  d: path("M29 12c-4.688-3.515-6-6-8-6s-2 1-3 1s-1-1-3-1s-3.313 2.485-8 6c-4 3-7 3-7 5s5 6 8 9c2 2 5 4 10 4s8-2 10-4c3-3 8-7 8-9s-3-2-7-5");
}

</style>
