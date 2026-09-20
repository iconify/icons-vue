<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yojol6byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="yojol6byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:time-2" /></template>
