<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um9u3vbqy.css';
import '../../css/k/kso7adcaj.css';
import '../../css/e/es25eccir.css';
import '../../css/i/ij2x_72vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGH9Ldddfs" class="um9u3vbqy"/></defs><g class="kso7adcaj"><circle class="es25eccir"/><use href="#SVGH9Ldddfs"/></g><g class="ij2x_72vy"><circle class="es25eccir"/><use href="#SVGH9Ldddfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:two-oclock" /></template>
