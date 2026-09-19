<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws9c__bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ws9c__bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:stopwatch-fill" /></template>
