<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzrofvbmd.css';
import '../../css/z/zdu6p8bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rzrofvbmd"/><path class="zdu6p8bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rocket" /></template>
