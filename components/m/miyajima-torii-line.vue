<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huapvubzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huapvubzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:miyajima-torii-line" /></template>
