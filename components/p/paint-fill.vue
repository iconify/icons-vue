<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxm4yjf1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxm4yjf1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:paint-fill" /></template>
