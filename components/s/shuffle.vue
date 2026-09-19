<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3mw5zbrj.css';
import '../../css/l/lf7w2ibjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="d3mw5zbrj"/><path class="lf7w2ibjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:shuffle" /></template>
