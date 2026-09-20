<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ver3u5bkf.css';
import '../../css/t/ta6kiz2pu.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/m/m1jc5t6-l.css';
import '../../css/u/u1v6mx2du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ver3u5bkf"/><path class="ta6kiz2pu"/><g class="ij2x_72vy"><path class="m1jc5t6-l"/><path class="u1v6mx2du"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:mountain" /></template>
