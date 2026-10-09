<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvjm-6b1r.css';
import '../../css/h/hn820sblx.css';
import '../../css/w/wkidug_7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mvjm-6b1r"/><path class="hn820sblx"/><path class="wkidug_7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mine-shaft-20-bold" /></template>
