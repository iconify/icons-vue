<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voz8zc88m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="voz8zc88m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:underline-text-1" /></template>
