<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kso7adcaj.css';
import '../../css/e/es25eccir.css';
import '../../css/s/sf9bepc3c.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/w/wdiib7zrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="kso7adcaj"><circle class="es25eccir"/><path class="sf9bepc3c"/></g><g class="ij2x_72vy"><circle class="es25eccir"/><path class="wdiib7zrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:twelve-thirty" /></template>
