<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zkg64ac6y"/><circle class="znku4abby"/><circle class="rp7mibb2l"/><circle class="queguraec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:speech-balloon" /></template>
<style>
.queguraec {
  cx: 10px;
  cy: 15px;
  r: 2px;
  fill: var(--svg-color--2a6797, #2a6797);
}

.rp7mibb2l {
  cx: 26px;
  cy: 15px;
  r: 2px;
  fill: var(--svg-color--2a6797, #2a6797);
}

.zkg64ac6y {
  fill: var(--svg-color--bdddf4, #bdddf4);
  d: path("M18 1C8.059 1 0 7.268 0 15c0 4.368 2.574 8.268 6.604 10.835C6.08 28.144 4.859 31.569 2 35c5.758-.96 9.439-3.761 11.716-6.416c1.376.262 2.805.416 4.284.416c9.941 0 18-6.268 18-14S27.941 1 18 1");
}

.znku4abby {
  cx: 18px;
  cy: 15px;
  r: 2px;
  fill: var(--svg-color--2a6797, #2a6797);
}

</style>
