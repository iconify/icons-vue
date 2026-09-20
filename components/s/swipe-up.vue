<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yytd03pef.css';
import '../../css/g/giadiac_x.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/n/n9o5dpb9y.css';
import '../../css/c/cnv0mofjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="yytd03pef"/><path class="giadiac_x"/><g class="ij2x_72vy"><path class="n9o5dpb9y"/><path class="cnv0mofjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:swipe-up" /></template>
