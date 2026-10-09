<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml8ltyb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ml8ltyb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:puzzle-48-bold" /></template>
