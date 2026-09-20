<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrtq4obqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrtq4obqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pencil-ai-fill" /></template>
