<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb1856a_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jb1856a_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:percentage" /></template>
