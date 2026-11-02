<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzsz40bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzsz40bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wechat-miniprogram-fill" /></template>
