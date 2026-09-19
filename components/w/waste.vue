<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rfrnaqb9j.css';
import '../../css/z/zk1d_9bxj.css';
import '../../css/u/urc6g4bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rfrnaqb9j"/><path class="zk1d_9bxj"/><path class="urc6g4bov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:waste" /></template>
