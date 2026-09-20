<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1l5eab0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j1l5eab0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-goal" /></template>
