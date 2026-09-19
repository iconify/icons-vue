<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnwv1pbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnwv1pbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:pie-chart-50" /></template>
