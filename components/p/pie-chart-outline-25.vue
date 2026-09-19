<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm4lw1-pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm4lw1-pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:pie-chart-outline-25" /></template>
