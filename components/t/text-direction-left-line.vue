<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inb8ybb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inb8ybb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-direction-left-line" /></template>
