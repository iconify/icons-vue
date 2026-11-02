<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b33gvabus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b33gvabus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:openai-fill" /></template>
