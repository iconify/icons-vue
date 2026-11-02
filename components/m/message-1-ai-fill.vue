<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2ft0mbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2ft0mbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-1-ai-fill" /></template>
