<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq9_gaclr.css';
import '../../css/e/e39ud6bwf.css';
import '../../css/k/kpnimx1ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="dq9_gaclr"/><circle class="e39ud6bwf"/><circle class="kpnimx1ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:overflow-menu-horizontal" /></template>
