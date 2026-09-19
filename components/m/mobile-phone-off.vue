<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="v3tcsqbdd"/><g class="n1mjunbsu"><path class="nj3sormvu"/><path class="gutck46bk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:mobile-phone-off" /></template>
<style>
.gutck46bk {
  d: path("M42.4 39.8v6.8H21.6v-32h20.8v9.8H45v-9.8c0-2.8-2.3-5-5.2-5H24.2c-2.9 0-5.2 2.2-5.2 5v35c0 2.8 2.3 5 5.2 5h15.6c2.9 0 5.2-2.2 5.2-5v-9.8zM32 52c-.9 0-1.6-.7-1.6-1.5S31.1 49 32 49s1.6.7 1.6 1.5S32.9 52 32 52");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.nj3sormvu {
  d: path("M32 37c-2.8 0-5-2.2-5-5s2.2-5 5-5s5 2.2 5 5s-2.2 5-5 5m0-8.6c-2 0-3.6 1.6-3.6 3.6s1.6 3.6 3.6 3.6s3.6-1.6 3.6-3.6s-1.6-3.6-3.6-3.6m7.5 8.6v-4.3H46v-1.4h-6.5v-2.9H46V27h-8v10zm9 0v-4.3H55v-1.4h-6.5v-2.9H55V27h-8v10z");
}

.v3tcsqbdd {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--eda454, #eda454);
}

</style>
