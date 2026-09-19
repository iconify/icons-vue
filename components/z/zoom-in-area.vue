<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgmyvbbuo.css';
import '../../css/q/qmvfbubxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rgmyvbbuo"/><path class="qmvfbubxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zoom-in-area" /></template>
