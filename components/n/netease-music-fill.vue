<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri8ga0brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri8ga0brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:netease-music-fill" /></template>
