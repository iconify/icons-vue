<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq6pcfb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nq6pcfb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:pie-chart" /></template>
