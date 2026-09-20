<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg8auor9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yg8auor9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tiktok" /></template>
