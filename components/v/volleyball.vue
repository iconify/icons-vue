<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsvenmjsn.css';
import '../../css/o/oik_dsbct.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/a/awtcwymkh.css';
import '../../css/q/qk57ujrcz.css';
import '../../css/i/iu92mo3zw.css';
import '../../css/y/ycxj5iv6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="lsvenmjsn"/><path class="oik_dsbct"/><g class="ij2x_72vy"><path class="awtcwymkh"/><path class="qk57ujrcz"/><path class="iu92mo3zw"/><circle class="ycxj5iv6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:volleyball" /></template>
