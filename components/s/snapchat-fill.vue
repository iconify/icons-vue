<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1wtusbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1wtusbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snapchat-fill" /></template>
