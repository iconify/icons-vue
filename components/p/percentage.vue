<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/t/tuvu8wjin.css';
import '../../css/q/qbegytbhw.css';
import '../../css/o/opakkwbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="tuvu8wjin"/><circle class="qbegytbhw"/><path class="opakkwbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:percentage" /></template>
