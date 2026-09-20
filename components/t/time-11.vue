<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcy55rw5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="gcy55rw5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:time-11" /></template>
