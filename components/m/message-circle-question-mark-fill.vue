<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg0obebbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg0obebbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-question-mark-fill" /></template>
