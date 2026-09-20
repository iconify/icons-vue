<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-m_vqxss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s-m_vqxss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:music-note-2-flat" /></template>
