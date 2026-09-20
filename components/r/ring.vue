<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0-jx1bpp.css';
import '../../css/k/kx_1d-sfu.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/x/xecxklbhv.css';
import '../../css/x/xfdyl25bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="a0-jx1bpp"/><path class="kx_1d-sfu"/><g class="ij2x_72vy"><circle class="xecxklbhv"/><path class="xfdyl25bs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ring" /></template>
