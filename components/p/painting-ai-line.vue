<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0dut0-fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0dut0-fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:painting-ai-line" /></template>
