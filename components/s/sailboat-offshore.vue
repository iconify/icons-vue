<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1n-pskbt.css';
import '../../css/y/yov2mac9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y1n-pskbt"/><path class="yov2mac9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sailboat-offshore" /></template>
