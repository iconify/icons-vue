<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuzmn-bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuzmn-bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sword-fill" /></template>
