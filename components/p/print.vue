<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg51_9s6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1536};
const content = `<path class="yg51_9s6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:print" /></template>
