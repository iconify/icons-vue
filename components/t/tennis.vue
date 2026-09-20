<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmd9t7b_r.css';
import '../../css/r/r-ox38ulx.css';
import '../../css/w/wki8h1byv.css';
import '../../css/n/nx7pbsbkk.css';
import '../../css/y/yzznlveym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="vmd9t7b_r"/><circle class="r-ox38ulx"/><path class="wki8h1byv"/><path class="nx7pbsbkk"/><circle class="yzznlveym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:tennis" /></template>
