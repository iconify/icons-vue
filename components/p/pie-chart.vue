<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huue4xb4c.css';
import '../../css/o/o6fdclsme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="huue4xb4c"/><path class="o6fdclsme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pie-chart" /></template>
