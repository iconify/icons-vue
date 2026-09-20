<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh2zvbb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh2zvbb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-talk-off-1" /></template>
