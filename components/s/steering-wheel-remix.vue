<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aei_ydl8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aei_ydl8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:steering-wheel-remix" /></template>
