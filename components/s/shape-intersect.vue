<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgtr2_73j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jgtr2_73j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shape-intersect" /></template>
