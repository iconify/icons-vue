<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm3ioub3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm3ioub3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:octagon-fill" /></template>
