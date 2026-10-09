<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu4o8i4pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uu4o8i4pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:woodchip-48" /></template>
