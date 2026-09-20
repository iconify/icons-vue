<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5hfnwz9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5hfnwz9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-chat-fill" /></template>
