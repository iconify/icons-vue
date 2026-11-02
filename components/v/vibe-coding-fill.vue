<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmgvc-bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmgvc-bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vibe-coding-fill" /></template>
