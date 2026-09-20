<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkv5dq48z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkv5dq48z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sun-fall-filled" /></template>
