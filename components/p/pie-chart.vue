<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2os1ubay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i2os1ubay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:pie-chart" /></template>
