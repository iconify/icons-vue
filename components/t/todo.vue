<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfttfe_2y.css';
import '../../css/r/rirt7bcol.css';
import '../../css/m/mxo2jdblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="rirt7bcol"/><path class="mxo2jdblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:todo" /></template>
