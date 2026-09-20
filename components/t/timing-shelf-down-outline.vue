<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh16x0bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yh16x0bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:timing-shelf-down-outline" /></template>
