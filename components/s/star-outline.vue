<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0kh8pbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y0kh8pbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:star-outline" /></template>
