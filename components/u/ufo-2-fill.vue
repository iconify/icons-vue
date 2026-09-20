<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thvvfsrjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thvvfsrjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ufo-2-fill" /></template>
