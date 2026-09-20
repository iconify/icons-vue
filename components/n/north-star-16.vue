<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag57fwbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ag57fwbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:north-star-16" /></template>
