<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7f0m03tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a7f0m03tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:rss-square" /></template>
