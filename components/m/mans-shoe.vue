<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un2i-lbfo.css';
import '../../css/f/f59rr5ugd.css';
import '../../css/i/i_u-dktcm.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/e/e_hfs4dyb.css';
import '../../css/t/t1jtnkbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="un2i-lbfo"/><path class="f59rr5ugd"/><path class="i_u-dktcm"/><g class="ij2x_72vy"><path class="e_hfs4dyb"/><path class="t1jtnkbje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:mans-shoe" /></template>
