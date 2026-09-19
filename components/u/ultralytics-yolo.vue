<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wngs4vr5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wngs4vr5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:ultralytics-yolo" /></template>
