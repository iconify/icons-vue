<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yihz5hb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yihz5hb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:markdown-fill" /></template>
