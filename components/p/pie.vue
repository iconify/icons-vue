<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp_f6gbzm.css';
import '../../css/q/qp5hhjbxf.css';
import '../../css/r/r9f97sbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="rp_f6gbzm"/><path class="qp5hhjbxf"/><path class="r9f97sbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:pie" /></template>
