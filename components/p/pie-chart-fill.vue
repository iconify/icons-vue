<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_bh4bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nz_bh4bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pie-chart-fill" /></template>
