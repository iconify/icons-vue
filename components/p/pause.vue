<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aml43npzb.css';
import '../../css/y/yf8s-acsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aml43npzb"/><path class="yf8s-acsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:pause" /></template>
