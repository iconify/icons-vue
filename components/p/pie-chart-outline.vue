<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckanf-3yy.css';
import '../../css/h/h-c11pbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ckanf-3yy"/><path class="h-c11pbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pie-chart-outline" /></template>
