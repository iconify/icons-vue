<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgppgjddj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgppgjddj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scan-2-fill" /></template>
