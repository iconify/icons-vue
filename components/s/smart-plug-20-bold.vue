<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whf-7i3fs.css';
import '../../css/d/dqs7t3alo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="whf-7i3fs"/><path class="dqs7t3alo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-plug-20-bold" /></template>
