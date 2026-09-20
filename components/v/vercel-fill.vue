<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f95irwlxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f95irwlxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vercel-fill" /></template>
