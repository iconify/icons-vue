<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyz4p1nzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyz4p1nzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:report-problem-filled" /></template>
