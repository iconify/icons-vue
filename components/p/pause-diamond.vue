<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb4f1dvhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb4f1dvhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pause-diamond" /></template>
