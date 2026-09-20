<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxftyu7ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:receipt-long-off-outline" /></template>
<style>
.fxftyu7ez {
  fill: currentColor;
  d: path("m21.11 22.53l-1.764-1.763q-.192.133-.42.183t-.387.05H6q-.846 0-1.423-.577T4 19v-2h3V8.421L1.887 3.308l.713-.714l19.223 19.223zM6 20h12.579l-2-2H5v1q0 .425.288.713T6 20m14-2.806l-1-1V5H7.806L7 4.194v-.81l1.27.885l1.307-.884l1.308.884l1.307-.884l1.308.884l1.308-.884l1.308.884l1.307-.884l1.308.884L20 3.384zM8 17h7.579L8 9.421zm3.317-8.5l-1-1h4.414v1zm3 3l-1-1h1.414v1zm2.028.04q-.23-.23-.23-.54t.23-.54t.54-.23t.539.23t.23.54t-.23.54t-.54.23t-.539-.23m.54-2.77q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.539.23t.23.54t-.23.54t-.54.23M5 20v-2z");
}

</style>
