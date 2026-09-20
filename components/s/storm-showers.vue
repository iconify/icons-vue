<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq8m6qynl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="pq8m6qynl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:storm-showers" /></template>
