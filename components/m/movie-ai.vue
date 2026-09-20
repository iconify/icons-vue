<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf5gxbc2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf5gxbc2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:movie-ai" /></template>
