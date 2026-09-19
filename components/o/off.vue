<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuyxq3b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yuyxq3b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:off" /></template>
