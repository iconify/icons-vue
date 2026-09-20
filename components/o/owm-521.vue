<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyujgibwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="zyujgibwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-521" /></template>
