<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbwcpk9oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbwcpk9oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:message-video" /></template>
