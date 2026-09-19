<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysq1xfblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ysq1xfblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:spray-can-sparkles" /></template>
