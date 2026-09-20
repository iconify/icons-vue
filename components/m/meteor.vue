<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrr6p3bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="rrr6p3bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:meteor" /></template>
