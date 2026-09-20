<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybmc9dbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ybmc9dbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:multi-select-16" /></template>
