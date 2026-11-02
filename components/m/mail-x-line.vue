<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyoc15fbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyoc15fbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-x-line" /></template>
