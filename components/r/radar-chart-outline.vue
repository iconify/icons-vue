<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6lk9v31w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p6lk9v31w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:radar-chart-outline" /></template>
