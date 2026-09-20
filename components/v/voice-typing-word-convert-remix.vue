<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu8d-fbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gu8d-fbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:voice-typing-word-convert-remix" /></template>
