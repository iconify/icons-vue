<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7ppq1bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t7ppq1bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:plugin-16" /></template>
