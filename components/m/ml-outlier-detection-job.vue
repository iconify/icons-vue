<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymonzhbhk.css';
import '../../css/w/wbjg6db2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ymonzhbhk"/><path class="ouiIcon__fillSecondary wbjg6db2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:ml-outlier-detection-job" /></template>
