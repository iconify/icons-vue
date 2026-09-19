<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdnhdf9mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zdnhdf9mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:triangle-down-outline" /></template>
