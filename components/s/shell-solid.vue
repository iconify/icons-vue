<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj1y1wbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj1y1wbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shell-solid" /></template>
