<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw3xaacjo.css';
import '../../css/g/gvz_-7xqa.css';
import '../../css/w/w5gcokbqt.css';
import '../../css/d/dc8kggb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="gvz_-7xqa"/><path class="w5gcokbqt"/><path class="dc8kggb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volleyball-20" /></template>
