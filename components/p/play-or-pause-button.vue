<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="noje9kb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:play-or-pause-button" /></template>
<style>
.noje9kb3p {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M67.68 95.55h18.03v-63.1H67.68zm36.05-63.1v63.09h18.03V32.45zm-97.49-.28v63.66L56.26 64z");
}

</style>
