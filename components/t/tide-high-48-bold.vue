<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yehyu3l8d.css';
import '../../css/m/m6mu15bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yehyu3l8d"/><path class="m6mu15bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tide-high-48-bold" /></template>
