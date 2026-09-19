<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/t/tutyhtbtf.css';
import '../../css/l/lvprdxdgh.css';
import '../../css/e/e-1ifub3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="tutyhtbtf"/><circle class="lvprdxdgh"/><path class="e-1ifub3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:people" /></template>
