<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb_7z4bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb_7z4bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:music-2-line" /></template>
