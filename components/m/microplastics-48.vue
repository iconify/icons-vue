<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja4f5ybie.css';
import '../../css/u/ug7yt43lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ja4f5ybie"/><path class="ug7yt43lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:microplastics-48" /></template>
