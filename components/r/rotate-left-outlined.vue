<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbb2-5bwt.css';
import '../../css/o/o855tz_5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cbb2-5bwt"/><path class="o855tz_5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:rotate-left-outlined" /></template>
