<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/keqt0zbld.css';
import '../../css/j/j41kocbsj.css';
import '../../css/b/b2vvr6bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="keqt0zbld"/><path class="j41kocbsj"/><path class="b2vvr6bvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-minimalistic-linear" /></template>
