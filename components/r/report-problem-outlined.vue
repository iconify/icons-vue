<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvn9s80eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvn9s80eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:report-problem-outlined" /></template>
