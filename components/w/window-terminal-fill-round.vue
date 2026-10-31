<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_atly8co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_atly8co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-terminal-fill-round" /></template>
