<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwgmocc6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vwgmocc6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tower-cooling" /></template>
