<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn7smsden.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn7smsden"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:task-2-line" /></template>
