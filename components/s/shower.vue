<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvsu1r03w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1792};
const content = `<path class="mvsu1r03w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:shower" /></template>
