<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s69omnchh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s69omnchh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-chat-line" /></template>
