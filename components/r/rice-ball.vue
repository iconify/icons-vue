<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfkn2s3yl.css';
import '../../css/i/iw3tibb8e.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/o/onxcbabva.css';
import '../../css/l/l-fhgubig.css';
import '../../css/a/a2hu4vb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="yfkn2s3yl"/><path class="iw3tibb8e"/><g class="ij2x_72vy"><path class="onxcbabva"/><path class="l-fhgubig"/><path class="a2hu4vb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:rice-ball" /></template>
