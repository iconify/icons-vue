<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c32l_ab_t.css';
import '../../css/y/yw2r-p6cc.css';
import '../../css/q/quz6tn28w.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/t/tg-jgkbxj.css';
import '../../css/b/bk6jshypl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="c32l_ab_t"/><path class="yw2r-p6cc"/><path class="quz6tn28w"/><g class="ij2x_72vy"><path class="tg-jgkbxj"/><path class="bk6jshypl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:safety" /></template>
