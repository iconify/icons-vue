<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx8nzig8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dx8nzig8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tree-view-alt" /></template>
