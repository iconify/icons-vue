<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":260};
const content = `<path class="fr78w4bdu"/><path class="po2mu-b5m"/><path class="kx3gvbcga"/><path class="g73013j_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:xata-icon" /></template>
<style>
.fr78w4bdu {
  fill: var(--svg-color--06d6a0, #06d6a0);
  d: path("M216.514 259.317c17.957-17.916 29.972-40.317 33.4-62.274c3.43-21.959-2.007-41.676-15.115-54.814l-67.708 67.55z");
}

.g73013j_v {
  fill: var(--svg-color--0076ff, #0076ff);
  d: path("M256 67.661a95.64 95.64 0 0 1-28.092 67.597l-.002-.003l-67.699 67.541a95.645 95.645 0 0 1 .158-135.257l.002.001L228.067 0A95.64 95.64 0 0 1 256 67.661");
}

.kx3gvbcga {
  fill: var(--svg-color--ff0075, #ff0075);
  d: path("M0 68.049a95.64 95.64 0 0 0 28.092 67.596l.001-.002l67.7 67.541a95.643 95.643 0 0 0-.159-135.258l-.001.002l-67.7-67.54A95.64 95.64 0 0 0 0 68.048");
}

.po2mu-b5m {
  fill: var(--svg-color--ffbe0b, #ffbe0b);
  d: path("M39.487 259.704C21.53 241.788 9.515 219.388 6.086 197.429s2.008-41.675 15.116-54.814l67.708 67.55z");
}

</style>
