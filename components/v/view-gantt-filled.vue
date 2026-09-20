<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr9frt1jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr9frt1jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:view-gantt-filled" /></template>
