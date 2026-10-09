<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf14hib5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mf14hib5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spring-48" /></template>
