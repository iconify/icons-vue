<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt2otpcin.css';
import '../../css/e/e6wnbobdo.css';
import '../../css/i/ik3n-9xvx.css';
import '../../css/r/r-exbihkf.css';
import '../../css/x/xc6115m2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dt2otpcin"/><path class="e6wnbobdo"/><path class="ik3n-9xvx"/><path class="r-exbihkf"/><path class="xc6115m2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:peertube" /></template>
