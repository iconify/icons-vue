<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znd_geczm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znd_geczm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openai-chatgpt" /></template>
