<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fszddsb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fszddsb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:signature-fill" /></template>
