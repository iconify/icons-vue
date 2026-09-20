<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnn8tebex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnn8tebex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wechat-2-fill" /></template>
