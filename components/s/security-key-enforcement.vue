<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9naz0aiw.css';
import '../../css/z/zh4vk3tqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9naz0aiw"/><path class="zh4vk3tqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:security-key-enforcement" /></template>
