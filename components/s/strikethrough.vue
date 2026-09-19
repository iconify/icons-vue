<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyuq8031z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="iyuq8031z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:strikethrough" /></template>
