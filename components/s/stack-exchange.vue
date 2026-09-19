<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th1r3u7ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1536};
const content = `<path class="th1r3u7ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:stack-exchange" /></template>
