<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frp7i3eut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frp7i3eut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:message-ai-3-line" /></template>
