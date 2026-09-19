<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfzbl7pcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfzbl7pcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tool-filled" /></template>
