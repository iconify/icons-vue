<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f93lqdbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f93lqdbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wechat-fill" /></template>
