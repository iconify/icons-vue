<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdo6hzbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hdo6hzbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:star3" /></template>
