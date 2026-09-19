<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyg7nbc4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1792};
const content = `<path class="wyg7nbc4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:venus-mars" /></template>
