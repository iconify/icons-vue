<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxa473bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxa473bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:nextjs-line" /></template>
