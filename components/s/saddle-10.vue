<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2jtvjb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="k2jtvjb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:saddle-10" /></template>
