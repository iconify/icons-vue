<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvsq1_bmx.css';
import '../../css/d/daf0krbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yvsq1_bmx"/><path class="daf0krbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:router-20-bold" /></template>
