<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3rdhabnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3rdhabnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wechat-channels-line" /></template>
