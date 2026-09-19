<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="y3w-di7bv"/><path class="ef7wevc0y"/><path class="hfqxcj39v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:tongue" /></template>
<style>
.ef7wevc0y {
  fill: var(--svg-color--ff717f, #ff717f);
  d: path("M8 29.1C8 12 8 17.2 32 17.2S56 12 56 29c0 17.1-10.7 25.6-24 25.6c-13.3.1-24-8.5-24-25.5");
}

.hfqxcj39v {
  fill: var(--svg-color--e2596c, #e2596c);
  d: path("M33.5 17.2L32 46.5l-1.5-29.3z");
}

.y3w-di7bv {
  fill: var(--svg-color--493b30, #493b30);
  d: path("M62 9.3c0 10.9-13.4 20.2-30 20.2S2 20.2 2 9.3c0 0 14.3 3.2 30 3.2s30-3.2 30-3.2");
}

</style>
