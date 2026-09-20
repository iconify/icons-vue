<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1wq2lbyq.css';
import '../../css/x/xwnryb42j.css';
import '../../css/s/sh--qnbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="y1wq2lbyq"/><path class="xwnryb42j"/><path class="sh--qnbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:oauth" /></template>
