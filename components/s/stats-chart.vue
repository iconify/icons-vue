<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxdn0e28r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sxdn0e28r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:stats-chart" /></template>
