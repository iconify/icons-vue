<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcy09zexs.css';
import '../../css/v/vani8sbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcy09zexs"/><path class="vani8sbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:pie-chart-outline" /></template>
