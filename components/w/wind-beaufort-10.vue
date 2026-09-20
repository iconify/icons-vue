<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuuw85byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="wuuw85byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-beaufort-10" /></template>
