<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4ed0ri_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j4ed0ri_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:strikethrough-16" /></template>
