<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t53h6xtlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t53h6xtlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:reflect-vertical" /></template>
