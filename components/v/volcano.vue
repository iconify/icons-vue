<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj-5f8bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="oj-5f8bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:volcano" /></template>
