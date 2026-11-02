<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqnxifbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqnxifbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-remove-2-line" /></template>
