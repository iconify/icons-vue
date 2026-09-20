<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2au1nh_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w2au1nh_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:saddle" /></template>
