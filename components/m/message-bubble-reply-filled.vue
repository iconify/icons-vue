<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4z-pxbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4z-pxbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-reply-filled" /></template>
