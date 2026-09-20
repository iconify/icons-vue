<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="czu0-fbyf"/><path class="hm9j458xh"/><path class="k_gb1nblq"/><path class="x5cboyulu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:pushpin" /></template>
<style>
.czu0-fbyf {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M23.651 23.297L12.702 12.348l9.386-7.821l9.385 9.385z");
}

.hm9j458xh {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M34.6 13.912a4.42 4.42 0 0 1-6.255 0l-6.257-6.256a4.426 4.426 0 0 1 6.257-6.258L34.6 7.656a4.423 4.423 0 0 1 0 6.256");
}

.k_gb1nblq {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M14 17.823S-.593 35.029.188 35.813S18.177 22 18.177 22z");
}

.x5cboyulu {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M25.215 27.991a4.423 4.423 0 0 1-6.258 0L8.009 17.041a4.425 4.425 0 0 1 6.258-6.256l10.948 10.949a4.424 4.424 0 0 1 0 6.257");
}

</style>
