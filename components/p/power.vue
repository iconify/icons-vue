<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh_3glbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nh_3glbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:power" /></template>
