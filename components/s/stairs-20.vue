<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1pq6-bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x1pq6-bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stairs-20" /></template>
