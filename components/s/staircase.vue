<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkvmcijwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zkvmcijwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:staircase" /></template>
