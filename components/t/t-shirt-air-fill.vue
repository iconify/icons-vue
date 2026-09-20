<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrw0g7hrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrw0g7hrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:t-shirt-air-fill" /></template>
