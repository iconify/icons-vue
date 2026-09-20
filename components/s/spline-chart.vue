<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvd31abxp.css';
import '../../css/u/uyos10o5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nvd31abxp"/><path class="uyos10o5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:spline-chart" /></template>
