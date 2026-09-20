<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2jl40bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r2jl40bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-dashboards" /></template>
