<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhrv8fevl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhrv8fevl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:pie-chart" /></template>
