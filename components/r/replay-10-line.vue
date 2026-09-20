<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwfatxbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwfatxbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:replay-10-line" /></template>
