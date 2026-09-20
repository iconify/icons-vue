<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd58x3bmx.css';
import '../../css/e/el5avswvr.css';
import '../../css/l/l41p0248x.css';
import '../../css/l/l_1bv1bce.css';
import '../../css/r/rxa9rtbju.css';
import '../../css/d/dnlw5ubyr.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/v/vy2ku-b-x.css';
import '../../css/v/v-pcj286g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fd58x3bmx"/><path class="el5avswvr"/><path class="l41p0248x"/><circle class="l_1bv1bce"/><path class="rxa9rtbju"/><path class="dnlw5ubyr"/><g class="jn8qy4bru"><circle class="vy2ku-b-x"/><path class="v-pcj286g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-chess-pawn" /></template>
