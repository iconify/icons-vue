<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkuaw6bpa.css';
import '../../css/e/e1qe98bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rkuaw6bpa"/><path class="e1qe98bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-20-bold" /></template>
