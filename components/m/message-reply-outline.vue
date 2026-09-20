<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkxkw_bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkxkw_bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-reply-outline" /></template>
