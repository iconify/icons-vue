<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":304};
const content = `<path class="mpt0htb9k"/><path class="vqr13zftw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:stackoverflow-icon" /></template>
<style>
.mpt0htb9k {
  fill: var(--svg-color--bcbbbb, #bcbbbb);
  d: path("M216.33 276.188v-81.211h26.953v108.165H0V194.977h26.954v81.211z");
}

.vqr13zftw {
  fill: var(--svg-color--f48023, #f48023);
  d: path("m56.708 187.276l132.318 27.654l5.6-26.604L62.31 160.672zm17.502-63.009l122.517 57.058l11.202-24.503L85.412 99.414zm33.955-60.208l103.964 86.462l17.152-20.653l-103.964-86.462zM175.375 0L153.67 16.102l80.511 108.515l21.703-16.102zM53.906 248.884h135.119V221.93H53.907z");
}

</style>
