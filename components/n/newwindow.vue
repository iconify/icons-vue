<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtmml6b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dtmml6b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:newwindow" /></template>
