<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj5d3u5yj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xj5d3u5yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:report-add" /></template>
