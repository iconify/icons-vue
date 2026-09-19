<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj_jthbsa.css';
import '../../css/w/w81_4cfys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj_jthbsa"/><path class="w81_4cfys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:pie-chart-fill" /></template>
