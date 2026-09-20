<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv_y32bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yv_y32bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:maze-arrow-right-short" /></template>
