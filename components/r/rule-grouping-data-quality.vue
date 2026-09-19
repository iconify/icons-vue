<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_s7ombqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b_s7ombqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rule-grouping-data-quality" /></template>
