<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yez44b7jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yez44b7jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:volume-down" /></template>
