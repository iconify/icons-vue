<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe-f4tbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fe-f4tbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:work-order-info-outline" /></template>
