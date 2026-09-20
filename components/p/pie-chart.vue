<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3_ohcbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="m3_ohcbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:pie-chart" /></template>
