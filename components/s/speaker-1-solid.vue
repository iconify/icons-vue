<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhkkb41cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zhkkb41cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:speaker-1-solid" /></template>
