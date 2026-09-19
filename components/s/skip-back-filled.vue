<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tos7grkdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tos7grkdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:skip-back-filled" /></template>
