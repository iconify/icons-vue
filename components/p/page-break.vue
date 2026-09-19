<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j90vc2a6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j90vc2a6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:page-break" /></template>
